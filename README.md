```perl

"! @ # $ % ^ & * ( !)"
"!! !@ !# !$ !% !^ !& !* !( @)"
"@! @@ @# @$ @% @^ @& @* @( #)"
"#! #@ ## #$ #% #^ #& #* #( $)"
"$! $@ $# $$ $% $^ $& $* $( %)"
"%! %@ %# %$ %% %^ %& %* %( ^)"
"^! ^@ ^# ^$ ^% ^^ ^& ^* ^( &)"
"&! &@ &# &$ &% &^ && &* &( *)"
"*! *@ *# *$ *% *^ *& ** *( ()"
"(! (@ (# ($ (% (^ (& (* (( !))"

!! = repeat command
@@ = add id
## = ctrl comment
$$ = ctrl scalar 
%% = ctrl split
^^ = ctrl peek
&& = ctrl runtime
** = ctrl permission accessor 
(( = paren statement
)) = close statement paren

```
```
!!: Repeat command
@@: Add ID
##: Control comment
$$: Control scalar
%%: Control split
^^: Control peek
&&: Control runtime
**: Control permission accessor
((: Paren statement
)): Close statement paren
```
```perl
##
#!/perl
####
import open index select system connect;
####

qw('readonly');

use english;
use warnings;
use charset utf8;
use console::debugger;


'! @ # $ % ^ & * ( !)'
'!! !@ !# !$ !% !^ !& !* !( @)'
'@! @@ @# @$ @% @^ @& @* @( #)'
'#! #@ ## #$ #% #^ #& #* #( $)'
'$! $@ $# $$ $% $^ $& $* $( %)'
'%! %@ %# %$ %% %^ %& %* %( ^)'
'^! ^@ ^# ^$ ^% ^^ ^& ^* ^( &)'
'&! &@ &# &$ &% &^ && &* &( *)'
'*! *@ *# *$ *% *^ *& ** *( ()'
'(! (@ (# ($ (% (^ (& (* (( !))'

'!!' = repeat command
'@@' = add id
'##' = ctrl comment
'$$' = ctrl scalar 
'%%' = ctrl split
'^^' = ctrl peek
'&&' = ctrl runtime
'**' = ctrl permission accessor 
'((' = paren statement
'))' = close statement paren

!!:= 'Repeat command'
@@:= 'Add ID'
##:= 'Control comment'
$$:= 'Control scalar'
%%:= 'Control split'
^^:= 'Control peek'
&&:= 'Control runtime'
**:= 'Control permission accessor'
((:= 'Paren statement'
)):= 'Close statement paren'

    use english;

'$!=declare'
    for EXAMPLE: set '$!' # declare statement 
        Sample:  @id set '$!' set 'ID' set command|@SET|confirm_chain;
'$@=verify'
    for EXAMPLE: '$!' >goto '$@' = { 'seq...gen' }
        Sample: $! $@user fetch( command >goto next available @CONDITIONAL; )
'$#=ctrl'
    for EXAMPLE: '$#' // command notes // CTRL command comments
'$$=scalar'
    for EXAMPLE: $$authenticator( 'parameter' open @ID user namespace )
'$%=hash'
    for EXAMPLE: $%DATA_LIST_DATA[ set $1 > $2 ]
'$^=peek'
    for EXAMPLE: $^peek_serial_DSN_DATA_QUERY
'$&=runtime'
    for EXAMPLE: '$&' runtime authenticator('$&' >goto command )
'$*=permission'
    for  EXAMPLE: '$*' in '$!' >goto 'command' {'set|command|code'}

'$(=open 'statement' n\'
    for EXAMPLE: import system >goto open command(:: select > connect index|source>confirm??) 
    
    sample: connect index from source;
    PAREN( ref: '~ ! @ # $ % ^ & * ( )' )

'$)=closed statement'
    for ALL statement(s) to work a statement must be 'addressed.'

    for seq gen str '$(' '$!' '$@' '$#' '$$' '$%' '$^' '$&' '$*' '$(' '$)';
