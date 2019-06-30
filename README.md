# todo
Display and edit simple todo lists.

### Usage

    $ todo         # displays the current todo list
    $ todo -c      # displays the current todo list in compact version (minus detail)
    $ todo -e      # edits the current todo list
    $ todo [kind]  # display [kind] todo's list instead of the default list (see todo lists).

The options work for any kind of todo list.

### TODO lists
By default there is a single todo list name current.todos located in ~/doc/todos. You can have an arbitary 
number of todo files. Running $ todos -e foo will start a foo.todos file in your editor. Once you save the 
file you now have another kind of todo's file. What you call thes are up to you.

TODO lists are simple text files. There is a simple format for them. 

A line starting with a star is a todo item. Any unstared lines following describe the todo in more detail. These lines are optional. 

Example:
* Handle missig $EDITOR var

If EDITOR is missing we should default to vim

* Add a usage statement
* Add vim swaps files to .gitignore

