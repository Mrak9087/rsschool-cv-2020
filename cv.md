# Maxim Romanenko

## Contact Info
    * E-mail: maks19-88@mail.ru
    * Skype: sirius5385
    * [GitHub](https://github.com/mrak9087/)

## Summary
For 10 years he worked as a system administrator. I have experience in programming in Delphi. He wrote clients for working with databases: MS SQL, MySQL, Firebird. I know SQL. Basic knowledge of Java. The institute had a course on HTMS, CSS. After graduation, I was engaged in page layout for some time. I love solving various puzzles. I want to become a professional developer. I am ready to develop in this direction.

## Skills
    * Delphi (Rad Studio)
    * HTML
    * CSS
    * JavaScript
    * JAVA
    * SQL

## Code
```
private void rotateClockwise(){
    int tmp[][] = new int[SIDE][SIDE];
    for (int i = 0; i < SIDE; i++) {
        for (int j = 0; j < SIDE; j++) {
            tmp[j][SIDE-i-1]=gameField[i][j];
        }
    }
    for (int i = 0; i < SIDE; i++) {
        for (int j = 0; j < SIDE; j++) {
            gameField[i][j]=tmp[i][j];
        }
    }
}
```