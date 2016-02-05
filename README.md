*version: 1.0*
*2016/01/26*

기재되지 않은 항목은 기본적으로 구글 스타일을 따른다.
쓰다가 맘에 들지 않는 부분이 있으면 하나하나 여기에 항목을 추가할 생각이다.

Coding Style Guide
--------------------------------------------------------------------------------------------------

*`#define` Guard*
* `<PROJECT>_<PATH>_<FILE>_H_`


*Naming*
* [구글 스타일](https://google.github.io/styleguide/cppguide.html#64-bit_Portability)을 따른다.
* 이유
  * 잘 정의되어있고 보기 쉽다. 
  * 많은 사람이 쓴다.
  * 내 스타일이 아닌 부분도 있지만 (type 과 variable 의 case 규칙이 다른점!!) 1 의 이유가 훨씬 더 중요하다.


* 예외사항
 * *"If you are naming something that is analogous to an existing C or C++ entity then you can follow the existing naming convention scheme."*
 * 파일명: .cpp, .h, .inc 를 쓴다.
 * 상수: k 를 붙이지 않는다. (start with Capital)
  * 이유: 구려서
 * 열거자: (start with Capital)


*indent style*
* [Allman style (BSD style)](https://en.wikipedia.org/wiki/Indent_style#Styles)
* use tab (not spaces)
* no indent for namespace
```c++
namespace acoross {
class FooBar
{
    ...
};
} //namespace acoross
```


*other format*
 * use google style
