# -if else.C
#练习
int main()
{
    int grade;
    printf("请输入您的成绩：");
    scanf("%d", &grade);

    if (grade >= 90)
        printf("A\n");
    else if (grade >= 80)
        printf("B\n");
    else if (grade >= 70)
        printf("C\n");
    else if (grade >= 60)
        printf("D\n");
    else
        printf("E\n");

    return 0;
}
