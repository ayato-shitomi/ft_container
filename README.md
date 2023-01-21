# ft_container

C++のSTDコンテナの再実装をする。

## 概要

### コンテナとは何ですか？

C++のSTDコンテナとは、C++の標準ライブラリで提供される、コンテナと呼ばれるデータ構造のクラスの集合です。コンテナとは、ある要素を他の要素と結びつけるために使用されるデータ構造のことです。

### 実装

再実装の条件としては、以下があげられます。

- 標準ライブラリーの使用が可能（コンテナの利用は不可能）
- 以下のコンテナの実装
	- vector
	- map
	- std::iterator_traits
	- std::reverse_iterator
	- std::enable_if
	- std::is_integral
	- std::equal and/or std::lexicographical_compare
	- std::pair
	- std::make_pair
