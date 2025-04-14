#include <stdio.h>
#include <string.h>

int main() {
    char alphabet[] = "abcdefghijklmnopqrstuvwxyz";
    char letter = 'l'; // Буква, которую нужно найти
    int index = -1;

    for (int i = 0; i < strlen(alphabet); i++) {
        if (alphabet[i] == letter) {
            index = i + 1; // +1, так как позиции в алфавите с 1, а индексы с 0
            break; // Выходим из цикла после нахождения буквы
        }
    }

    if (index != -1) {
        printf("Буква '%c' находится на позиции %d в алфавите\n", letter, index);
    } else {
        printf("Буква '%c' не найдена в алфавите\n", letter);
    }

    return 0;
}
