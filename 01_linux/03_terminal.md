# Terminal

Answer the following questions:

1. What does the `man` command do? Type in man rm. How do you scroll and get out?
1- il comando man rm mi da le istruzioni del comando rm, posso scrollare e uscire con il tasto q 
2. Look at the man page for ls. What does the -l flag do? What does the -a flag do?
2- con -a mi dice di non ignorare cio’ che inizia per..
3. How do you jump between words in the terminal?
3- ESC+B
4. How do you get to the end of a line in terminal?
4- fn+>
5. How do you move your cursor to the beginning in terminal?
5- CTRL+A oppure fn+<
6. How do you delete a word (without pressing backspace multiple times) in terminal?
6- CTRL+U = Cancella  a sinistra del cursore
    CTRL+K = Cancella a destra del cursore
7. What is the difference between a terminal and shell?
7- La shell è il programma che effettivamente legge
l'input e restituisce l'output. La shell tiene anche la cronologia dei
comandi e può gestire anche processi in background. Un esempio di shell
può essere **Bash**, la shell più utilizzata sui sistemi operativi Linux.

Il terminale, invece, è il programma che esegue la shell. In informatica,
questo tipo di programma è chiamato: "wrapper", involucro, ovvero quel
programma che ne ricopre un'altro. Il terminale, quindi, ti permette di
accedere alla shell e a lui, di fatto, non interessa quale shell sia
installata.
8. What is a `flag` (like `-la` in `ls -la`)? Give three examples of flags you have used.
8- i flag sono delle opzioni dei comandi 
9. What do the r and f flags do with the rm command?
9- rm -r cancella le cartelle e il loro contenuto
    rm -f ignora i file e gli argomenti inesistenti
