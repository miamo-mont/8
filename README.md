# 8
int main()
{
	int i = 0;
	int ret = 1;
	float sum = 0;
	int n = 0;
	scanf("%d", &n);
	for (i = 1; i <= n; i++)
	{
		ret = ret * i;
		sum = sum + 1 / (static_cast<float>(ret));


	}
	printf("%f", sum);
}
