#include <stdio.h>
#include <string.h>

int main() {
    char word[] = "yellow";
    char result[4]; // Массив для результата ("low\0")
    int start = 3; // Начальная позиция подстроки
    int end = 6;   // Конечная позиция подстроки

    int j = 0; // Индекс для массива result
    for (int i = start; i < end; i++) {
        result[j] = word[i];
        j++;
    }
    result[j] = '\0'; // Добавляем нуль-терминатор

    printf("Результат: %s\n", result);

    return 0;
}
