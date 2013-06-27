This porting makes blackboard no longer rely on color-theme package,
since Emacs has it's theme mechanism from Emacs 24.

### How to use:
1. First, add a local directory to custome-theme-load-path,
   `(add-to-list 'custom-theme-load-path "~/home/$USER/drop/the/theme/to")`
2. Then drop this theme into it
3. `M-x load-theme`, then choose blackboard, it should work, or, simple use `(load-theme 'blackboard t)` to enable the theme from start.

![screenshot](http://farm8.staticflickr.com/7404/9146526433_b3408a616d.jpg)
