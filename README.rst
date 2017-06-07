====================
 ``presenter-mode``
====================

Presenter-mode lets you page trough source code in Emacs as if it were a slide deck. Special comments indicate slide boundaries, titles, and parts of the code that you do not want to see in the slides.

Keybindings
===========

In ``presenter-design-mode``
----------------------------

===============  ============================
Key              Action
===============  ============================
``C-c C-0``      Insert hidden block markers
``C-c C-1``      Insert a level-1 title
``C-c C-2``      Insert a level-2 title
``C-c C-3``      Insert a level-3 title
``C-c C--``      Insert a slide separator
``C-c C-w C-0``  Toggle region between hidden block markers
``C-c C-w C-1``  Toggle region between level-1 title
``C-c C-w C-2``  Toggle region between level-2 title
``C-c C-w C-3``  Toggle region between level-3 title
===============  ============================

In ``presenter-mode``
---------------------

===========  ===============================
Key          Action
===========  ===============================
``<prior>``  (Page Up)  Go to previous slide
``<next>``   (Page Down)  Go to next slide
``<f5>``     Recenter titles
===========  ===============================
