beutertail
==========

Newsbeuter / RSSTail / MultiTail utilities

A set of scripts to use a newsbeuter RSS urls file as the basis for rsstail/multitail input.

Copy scripts to your path (e.g., /usr/local/bin/ or ~/bin/)

Example of use (apologies for ugliness):

    eval multitail  -F .multitail.conf --no-load-global-config \
        -CS rsstail $( newsbeuter2rsstail  ~/.newsbeuter/urls  )
