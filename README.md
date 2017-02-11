# hello-world
long fun(long id)
{
_asm{pushad

mov edx,id     //就这一句出现内存访问违规

popad}


return (0)
}
