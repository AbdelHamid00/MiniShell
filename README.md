# Mini_shell #

School project made by me and a coTeam @Akhouya .

An implementation of a shell , with limited features ofc .
# Prerequisites for making this code run proprely :
You need a computer hahahaha , anyway ... lets continue 

For MacOs and Linux users, For windows users go use WSL .

You need a C compiler + The GNU Readline Library installed in your machine . That's all .
# To use or test my code :
Run the folowing commandes after cloning this repo 

    ◦ cd MiniShell
    
    ◦ make all 
    
    ◦ ./minishell
    
 Go a head and write in the prompt to run your commandes .
 
# Features :
• Display a prompt when waiting for a new command.

• Have a working history.

• Search and launch the right executable (based on the PATH variable or using a
relative or an absolute path).

• Not use more than one global variable. Think about it. You will have to explain
its purpose.

• Not interpret unclosed quotes or special characters which are not required by the
subject such as \ (backslash) or ; (semicolon).

• Handle ’ (single quote) which should prevent the shell from interpreting the metacharacters in the quoted sequence.

• Handle " (double quote) which should prevent the shell from interpreting the metacharacters in the quoted sequence except for $ (dollar sign).

• Implement redirections:

    ◦ < should redirect input.
    
    ◦ > should redirect output.
    
    ◦ << should be given a delimiter, then read the input until a line containing the
       delimiter is seen. However, it doesn’t have to update the history!
    ◦ >> should redirect output in append mode.
    
• Implement pipes (| character). The output of each command in the pipeline is
connected to the input of the next command via a pipe.

• Handle environment variables ($ followed by a sequence of characters) which
should expand to their values.

• Handle $? which should expand to the exit status of the most recently executed
foreground pipeline.

• Handle ctrl-C, ctrl-D and ctrl-\ which should behave like in bash.

• In interactive mode:

    ◦ ctrl-C displays a new prompt on a new line.
    
    ◦ ctrl-D exits the shell.
    
    ◦ ctrl-\ does nothing.
    
• Your shell must implement the following builtins:

    ◦ echo with option -n
    
    ◦ cd with only a relative or absolute path
    
    ◦ pwd with no options
    
    ◦ export with no options
    
    ◦ unset with no options
    
    ◦ env with no options or arguments
    
    ◦ exit with no options
    
