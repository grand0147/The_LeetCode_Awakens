

### Trie

[Wiki](https://www.wikiwand.com/zh-tw/Trie)
> Trie 稱前綴樹或字典樹，是一種有序樹，用於保存關聯數組，其中的鍵通常是字符串。
與二元搜尋樹不同，鍵不是直接保存在節點中，而是由節點在樹中的位置決定。一個節點的所有子孫都有相同的前綴，也就是這個節點對應的字符串，而根節點對應空字符串。
一般情況下，不是所有的節點都有對應的值，只有葉子節點和部分內部節點所對應的鍵才有相關的值。

![一個保存了8個鍵的trie結構，"A", "to", "tea", "ted", "ten", "i", "in", and "inn".](../img/500px-Trie_example.svg.png?raw=true "一個保存了8個鍵的trie結構")


### 用途
1. Autocomplete
2. Spell checker
3. IP routing (Longest prefix matching)
4. T9 predictive text
5. Solving word games

[Editorial Solution](https://leetcode.com/articles/implement-trie-prefix-tree/)
 
