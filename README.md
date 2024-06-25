
#include <stdio.h>

int main()
{
    int x,y,z;
  scanf("%d%d%d",&x,&y,&z);
  if(x<=y&&x<=z)
  {
      printf("x is small");
  }else if(y<=z&&y<=x)
  {
      printf("y is small");
  }else if(z<=x&&z<=y)
  {
      printf("z is small");
  }


    return 0;
}
