## Thai Word Segmentation port to .NET Standard 2.0 

Dictionary text segmentation

## Usage

```csharp
using THSplit;
public void TestSplit1() {
    Spliter spliter = new Spliter();
    string test = "นายจะไปไหนหรอ";
    var output = spliter.SegmentByDictionary(test);
}
```