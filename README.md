- 👋 Hi, I’m @zhangWwei
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
zhangWwei/zhangWwei is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


# include <stdio.h>

int main()
{

    char arr1[] = {"abcdefg hello"};
    char arr2[] = {"#############"};

    //int right = sizeof(arr1)/sizeof(arr1[0]);
    int right = strlen(arr1) - 1;
    int left = 0;

    while(left <= right)
    {

        arr2[left] = arr1[left];
        arr2[right] = arr1[right];
        left++;
        right--;

        printf("%s\n", arr2);
    }

  return 0;
}
