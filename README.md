# C-iniFileLoadSave
C#iniFileLoadSave
설정파일 읽기 저장하기
STM32에도 설정파일을 만들어 통신을 통해 MCU설정 가능하다
string[] stringSeparators = new string[] { "\r\n" };
string[] lines = text.Split(stringSeparators, StringSplitOptions.None);
Console.WriteLine("Nr. Of items in list: " + lines.Length);
foreach (string s in lines) {
  Console.WriteLine(s);...

  이런식으로 Text 창의 내용을 파싱할 수도 있음
