# Kogane Vowel Table

ひらがなやカタカナの母音を管理するクラス

## 使用例

```cs
using Kogane;
using UnityEngine;

public class Example : MonoBehaviour
{
    private void Start()
    {
        Debug.Log( VowelTable.Get( "か" ) ); // あ
        Debug.Log( VowelTable.Get( "き" ) ); // い
        Debug.Log( VowelTable.Get( "く" ) ); // う
        Debug.Log( VowelTable.Get( "け" ) ); // え
        Debug.Log( VowelTable.Get( "こ" ) ); // お
    }
}
```