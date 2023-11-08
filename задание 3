#include <iostream>

using namespace std;

int main()
{
	setlocale(0, "");

	const int ARRSIZE = 10;

	int arr[ARRSIZE] = {
		4, 1, 8, 8, 3, 6, 0, 7, 9, 4
	};

	cout << "Размер массива: " << ARRSIZE << endl;

	int sum = 0;

	for (int i = 0; i < ARRSIZE; i++)
	{
		cout << "Число " << arr[i] << " является '" << i + 1 << "' элементом в массиве" << endl;

		if (arr[i] % 3 == 0)
		{
			sum += arr[i];
		}
	}

	cout << "Суммой всех чисел кратных 3 будет: " << sum;
}
