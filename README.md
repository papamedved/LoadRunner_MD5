//MD5 algorithm for loadrunner

#include "lrs.h"
#include "md5.h"

Action()
{

char *s="12345abc";
char *dest=(char *) malloc(10*1024);

GetMd5FromString(s,dest);
lr_message(dest);

return 0;
}
