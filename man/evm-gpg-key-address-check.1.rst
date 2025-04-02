..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


====================================
evm-gpg-key-address-check
====================================

------------------------------------------------------
EVM GNU Privacy Guard Key Address Check tool
------------------------------------------------------
:Version: evm-gpg-key-address-check |version|
:Manual section: 1

Synopsis
========

evm-gpg-key-address-check *[options]* *key_file* *evm_address*


Description
===========

It verifies whether the 'email' address for
the target key file corresponds
to one for the input EVM address.


Options
========

-H  gnupg_home          GnuPG home (for when the signature type
                        is 'fingeprint').

-h                      Display help.
-c                      Enable color output
-v                      Enable verbose output


Bugs
====

https://github.com/themartiancompany/evm-gpg-key-address-check/-/issues

Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* gpg
* gpg-key-info
* gpg-signature-verify
* evm-gpg

.. include:: variables.rst
