# Ssangyong_Mybatis

  - 개요
    - 교육센터에서 배운 내용과 함께 새롭게 배우는 지식들을 담으려고 함.
    - <b>편의상 태그에 대한 꺽쇠는 () 으로 대체하려고 함.
    
  - <h3>ibatis 비교 지원 태그</h3>
    - isNull : "널일경우"
    - isNotNull : "널이아닐경우"
    - isEmpty : "공백일경우"
    - isNotEmpty : "공백이아닐경우"
    - isGreaterTan : ">"
    - isGreaterEqual : ">="
    - isLessThan : "<"
    - isLessEqual : "<="
    - isEqual : "=="
    - isNotEqual : "!="
    * Mybatis 에서는 isNull, isEmpty 등을 지원하지 않음!!(일부는 지원하나..?)
   
 - <h3>Mybatis 비교 지원 태그</h3>
   - if  : 단일 조건문
  - ex) <if test="str != null and str != ''"></if>
     - equals(), toString(), equalsIgnoreCase() 도 쓸수 있음.
     - &&, || 대신 and, or 를 사용함.
  
   - <choose> <when> <otherwise> : 다중 조건문
    
   
