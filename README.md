# CompilersLab3556
This Folder Consist Of Following Programs.......

**ifelse** --->for given "if" statement doesnt have a corresponding "else" statement then add an empty "else{}" statement.

**constantfolding** --->it generates constant folding for a given block of statements and generates optimized three address statements for that block.

**boolean** --->Backpatches ifelse statement,loop and array .

**forwhile** --->convert the given "for" and "dowhile" loop to "while" loop such that its semantic meaning is maintained.

**symbol_table** --->generates symbol table for given program.

**labelledtree** --->creates label tree for given program.

**threeaddr** ---> creates three address statements for given program.

**syntaxtree** --->creates syntax tree for given program.

**Dag** --->generates dag from given set of c statements for a basic block. it generates leaders and blocks and dag for each blocks.

**To Execute lex and yacc programs**
/*for c program*/

lex filename.l
yacc -d filename.y
gcc lex.yy.c y.tab.c
./a.out


/*for c++ program*/

lex filename.l
yacc -d filename.y
g++ lex.yy.c y.tab.c -lfl
./a.out
