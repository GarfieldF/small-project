# Customizing_tmux
how to use tmux with a customized configuration for yourself

    cat tmux.conf >> ~/.tmux.conf

 Enable mouse control
 
## Common shortcuts and command

   + ctrl+a d : detach
   
   + ctrl+a x  : kill this panel
   
   + ctrl+a -  : horizontially split windows
   
   + ctrl+a | : to vertically split windows
   + Alt+arrow/directly click : switch panes
   
    tmux # To create a new tmux session
    tmux a #To reconnect to last detached session 
    
    tmux list-sessions # list all sessions
    tmux attach-session -t $session_name$ # connect arbitary session
    tmux a -t mysession # same as above one


## Reference links
[Making tmux Pretty and Usable - A Guide to Customizing your tmux.conf](https://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/ "With a Title"). 

[A Quick and Easy Guide to tmux](https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/)

[The Tao of tmux](https://leanpub.com/the-tao-of-tmux/read)

[A tmux Crash Course](https://thoughtbot.com/blog/a-tmux-crash-course)
