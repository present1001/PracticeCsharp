## async
非同期であることを指定します。     
の修飾子が使用されているメソッドまたは式を、"非同期メソッド" と呼びます。    
https://docs.microsoft.com/ja-jp/dotnet/csharp/language-reference/keywords/async


## Async および Await を使用した非同期プログラミング 
https://docs.microsoft.com/ja-jp/dotnet/csharp/programming-guide/concepts/async/index
    （サンプルソース付き）

## partial（部分クラスと部分メソッド）
https://docs.microsoft.com/ja-jp/dotnet/csharp/programming-guide/classes-and-structs/partial-classes-and-methods
    
クラス、インターフェイス、メソッドの定義を、複数のソースに分割できる。    
（コンパイル時に結合）
```cs
public partial class Employee
{
    public void DoWork()
    {
    }
}

public partial class Employee
{
    public void GoToLunch()
    {
    }
}
```