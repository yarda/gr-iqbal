# Copyright 2011 Free Software Foundation, Inc.
#
# This file is part of gr-iqbalance
#
# gr-iqbalance is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# gr-iqbalance is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with gr-iqbalance; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street,
# Boston, MA 02110-1301, USA.

install(FILES
    iqbalance_fix_cc.block.yml
    iqbalance_optimize_c.block.yml
    iqbalance.tree.yml
    DESTINATION share/gnuradio/grc/blocks
)
