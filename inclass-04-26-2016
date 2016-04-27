main()
{
  print.myname(&myname[0]);
}
print_myname(char * cptr)
{
  if(*cptr == 0) return;
  print *cptr;
    cptr++;
    print_myname(cptr)
}

for(;i*cptr; cptr++)
{ 
  print *cptr;
}

.data
name: .asciiz "my name"

.text
.globl main
main:
la $a1, name
addi $sp, $sp, -4
sw $a1, 0($sp)
jal print_myname
addi $sp, $sp, 4
v0 <- 10
syscall

print_myname:
  lw $t0, 0($sp)
  lw $t1, 0($t0)
  #if -beq $t1, $0, done
  #else  a0 -> stack
  #      a0 <- t0
  #      v0 <- 11?
        syscall
        a0 <- stack
