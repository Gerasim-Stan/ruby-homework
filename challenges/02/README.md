# Чертане на морски шах

Всеки е играл морски шах.

Нека имаме списъчно представяне на дъска за морски шах, за което е вярно:

- Съставена е от списък с точно девет елемента.
- Възможните елементи са или `nil` за празно поле, или символът `:x` за поле, в което има "x", или `:o` за поле, в което има `o`.
- Първите три елемента съответстват на първия ред от дъската, вторите три – на втория ред и последните три на третия ред.

От вас ще искаме да напишете код, който да обръща това списъчно представяне на дъската към текстова рисунка. Най-лесно ще е да илюстрираме с пример.

Ако имаме следната дъска:

    tic_tac_toe_board = [
      nil, nil, :x,
      :o,  nil, :x,
      :o,  :x,  :o,
    ]

То ще искаме от вас да дефинирате метода `render_tic_tac_toe_board_to_ascii(board)`, който да върне следният текстов низ:

    "|   |   | x |
    | o |   | x |
    | o | x | o |"

Ако изведем на екрана така получения низ, ще видим следната близка до реалността рисунка:

    |   |   | x |
    | o |   | x |
    | o | x | o |

## Бележки

- Не извеждайте нищо на екрана.
- Използвайте само `\n` за разделяне на редовете. Можете да го направите, като сложите `\n` в низ с двойни кавички: `"\n"`.
- Няма да ви подаваме некоректни данни. Списъците, с които ще тестваме, винаги ще имат точно девет елемента и елементите винаги ще са един от трите изброени.

С това предизвикателство ще трябва да упражните обхождане и манипулация на списъци и операции с низове. Нашето решение се побира в 270 символа и е сравнително описателно.

## Примерен тест

Примерните тестове се намират в [GitHub хранилището с домашните](https://github.com/fmi/ruby-homework/blob/master/challenges/02/sample_spec.rb). За информация как да ги изпълните, погледнете [README-то на хранилището](https://github.com/fmi/ruby-homework#readme).
