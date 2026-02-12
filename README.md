$\color{#ffa550}{\LARGE\text{Nameless┈Compiler}}$  
  
$\text{\textcolor{#5d6393}{These }\textcolor{#5078b4}{compile scripts}\textcolor{#5d6393}{ are used to enforce }\textcolor{#5078b4}{file structure}\textcolor{#5d6393}{ in polyglot application}}$  
$\text{\textcolor{#5d6393}{Copy one for each source code module and add *.compile to }\textcolor{#5078b4}{.gitignore}\textcolor{#5d6393}{. These will  }}$  
$\text{\textcolor{#5d6393}{live with the }\textcolor{#5078b4}{module}\textcolor{#5d6393}{ which they }\textcolor{#5078b4}{compile}\textcolor{#5d6393}{. The script recognizes which compiler to  }}$  
$\text{\textcolor{#5d6393}{use for any given source file based on the name. If }\textcolor{#5078b4}{something}\textcolor{#5d6393}{ is missing, add it }}$  
$\text{\textcolor{#5d6393}{as the command with the }\textcolor{#5e8eed}{cmd}\textcolor{#5d6393}{ variable or expand the }\textcolor{#5e8eed}{Identify}\textcolor{#5d6393}{ function for scaling}}$  
  
$\text{\textcolor{#5d6393}{The system also creates backups. Use }\textcolor{#5e8eed}{--dryrun}\textcolor{#5d6393}{ for more detailed flow information}}$  
  
$\text{\textcolor{#5d6393}{Use the }\textcolor{#5e8eed}{--bright}\textcolor{#5d6393}{ flag to make the compile text more }\textcolor{#5078b4}{visible}}$  
$\text{\textcolor{#5d6393}{Avoid manual compiling in the cli; }\textcolor{#5078b4}{consistently}\textcolor{#5d6393}{ using the nameless compiler as a}}$  
$\text{\textcolor{#5d6393}{static script eliminates }\textcolor{#5078b4}{ambiguity}\textcolor{#5d6393}{ for ai models and avoids }\textcolor{#5078b4}{filesystem pollution}}$  
$\text{\textcolor{#5d6393}{Models are able to deduce from the file names that this }\textcolor{#5078b4}{nameless}\textcolor{#5d6393}{ compiler should}}$  
$\text{\textcolor{#5d6393}{be used without special instruction to do so.}}$  
  
$\text{\textcolor{#5d6393}{Nameless is most effective with }\textcolor{#5078b4}{src/}\textcolor{#5d6393}{ and }\textcolor{#5078b4}{bin/}\textcolor{#5d6393}{ equivalents  consistent throughout}}$  
  
$\text{\textcolor{#5d6393}{The }\textcolor{#5078b4}{fs}\textcolor{#5d6393}{ may be clean but forms of }\textcolor{#5078b4}{ai related pollution}\textcolor{#5d6393}{ may require other measures}}$  
  
$\text{\textcolor{#2f334d}{Flags:}}$  
    $\text{\textcolor{#5e8eed}{    --help             }\textcolor{#5d6393}{Display this text and exit}}$  
    $\text{\textcolor{#5e8eed}{    --bright           }\textcolor{#5d6393}{Make the dark text lighter}}$  
    $\text{\textcolor{#5e8eed}{    --dryrun           }\textcolor{#5d6393}{View what the script would do and directories used}}$  
    $\text{\textcolor{#5e8eed}{    --nobak            }\textcolor{#5d6393}{Skip making a backup at all, instead replacing the binary}}$  
    $\text{\textcolor{#5e8eed}{    --prune            }\textcolor{#5d6393}{Remove backups older than the 10ᵗʰ}}$  
    $\text{\textcolor{#5e8eed}{                           }\textcolor{#5d6393}{The nobak and prune modes can be persistently enabled}}$  
    $\text{\textcolor{#5e8eed}{                           }\textcolor{#5d6393}{in config, along with the number of backups to retain}}$  
  
  
  
  
  
  
  
$\color{#5d6393}{}$
<img width="1920" height="653" alt="Screenshot From 2026-02-12 02-14-01" src="https://github.com/user-attachments/assets/47f0fbb7-c1a5-4aa1-8b1e-9c515405c440" />  

$\color{#5d6393}{\text{The default prune settings would prevent this many backups from accumelating}}$  


<img width="1920" height="582" alt="image" src="https://github.com/user-attachments/assets/eaca280b-5788-4b10-a5e5-89c3a8dc2b18" />  

$\color{#5d6393}{\text{With prune enabled, the excess backups were deleted, while 10 were retained as backups}}$
$\color{#5d6393}{\text{This can be easily changed to a lower number and backups may also be disabled entirely}}$
