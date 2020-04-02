# captdriver

## Foreword
Are you still using an older Canon laser printer that doesn't support
network printing, PCL or EPS? Do you use an operating system other than
macOS or Microsoft Windows, and have trouble getting Canon's drivers to 
work? Or are you simply averse to the practice of installing 32-bit 
dependencies on a 64-bit system?

**Captdriver is a free (as in speech) alternative driver** for Canon 
printers that can only accept the proprietary CAPT data stream format.
It aims to be a reliable and truly portable alternative driver for
alternative operating systems such as GNU/Linux. Being free and open
source, you can take part in its development too, and help with
expanding support, adding new features, and most importantly, maintaining
its codebase.

As Captdriver is almost completely written in C, and dependent only on
the Common Unix Printing System (*CUPS*), it is potentially compatible
with any operating system with a working copy of CUPS.

As a bonus for users on 64-bit x86 hardware, Captdriver eliminates the
need to run 32-bit binaries on your 64-bit operating system.

## Status
Captdriver is currently admittedly far from complete and many extra 
features are still missing, but it's rather reliable for what it's
capable of.

Three printers are supported: LBP2900, LBP3000 and LBP3010, with any paper
size from the width and height of an ISO A6 up to US Legal. Only 600dpi
resolution is available for now.

## Acknowledgements
This driver is an onging work in progress, based on the works of
Rildo Pragana, Nicholas Boichat, Alexey Galakhov, Benoit Bolsee as
well as Vitaliy Tomin.

## Installation and Setup
This software must be manually installed. Please refer to Mounaiban's
Captdriver Wiki for detailed instructions at https://github.com/mounaiban/captdriver/wiki.

## Technical Information
Details of the CAPT format, including printer control
protocols, status registers and compression algorithms are
documented in the `SPECS` file. While incomplete and expected to
contain errors and omissions, help with expanding it and making
corrections is greatly appreciated. Please also check the [wiki] 
for more information on the scope and status of this project.

## Disclaimers
Please use this driver at your own risk. As with any software licensed
under the *GNU General Public License 3.0*, there is NO WARRANTY.
Full terms and conditions are detailed in the file named `COPYING`.

This is unofficial software not endorsed by Canon Inc. or any of its
affiliates.

CUPS and macOS are trademarks of Apple Inc.

Windows is a trademark of Microsoft Corporation.

[ibm]: https://www-01.ibm.com/support/docview.wss?uid=nas8N1019527 "IBM. IBM Information on Printers by Canon. IBM Support. 
Reference #N1019527. Updated 2017-03-28."

[wiki]: https://github.com/mounaiban/captdriver/wiki "Mounaiban's captdriver Wiki."
