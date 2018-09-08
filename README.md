# Overview

A sample collection of TypeScript 's Array extension method.

# System requirements

* Node.js 8.x
* TypeScript 2.9.x  
* jest 23.x (Unit Test)

# Extension Method list

## Array

<table>
  <tr>
    <th>Extension Method</th>
    <th>TypeScript file</th>
    <th>C# LINQ</th>
    <th>Overview</th>
  </tr>
  <tr>
    <td>select</td>
    <td><a href="./src/ext/array/alias-linq.ts">./src/ext/array/alias-linq.ts</a></td>
    <td>Select</td>
    <td>
      配列の各要素を新しい配列に射影します。<br />
      Array.map をラッピングしています。
    </td>
  </tr>  
  <tr>
    <td>where</td>
    <td><a href="./src/ext/array/alias-linq.ts">./src/ext/array/alias-linq.ts</a></td>
    <td>Where</td>
    <td>
      配列の指定した条件で抽出します。<br />
      Array.filter をラッピングしています。
    </td>
  </tr>  
  <tr>
    <td>all</td>
    <td><a href="./src/ext/array/alias-linq.ts">./src/ext/array/alias-linq.ts</a></td>
    <td>All</td>
    <td>
      配列のすべての要素が条件を満たすかどうか判定します。<br />
      Array.every をラッピングしています。
    </td>
  </tr>  
  <tr>
    <td>skip</td>
    <td><a href="./src/ext/array/alias-linq.ts">./src/ext/array/alias-linq.ts</a></td>
    <td>Skip</td>
    <td>
      先頭から指定された数の要素をスキップし、残りの配列を返します。<br />
      Array.slice をラッピングしています。
    </td>
  </tr>  
  <tr>
    <td>take</td>
    <td><a href="./src/ext/array/alias-linq.ts">./src/ext/array/alias-linq.ts</a></td>
    <td>Take</td>
    <td>
      配列の先頭から指定した数の要素を返します。<br />
      Array.slice をラッピングしています。
    </td>
  </tr>

  <tr>
    <td>any</td>
    <td><a href="./src/ext/array/any.ts">./src/ext/array/any.ts</a></td>
    <td>Any</td>
    <td>
      条件にあうデータが1件でもある場合、true
    </td>
  </tr>  

  <tr>
    <td>sum</td>
    <td><a href="./src/ext/array/calc.ts">./src/ext/array/calc.ts</a></td>
    <td>Sum</td>
    <td>
      数値配列の合計値を取得します。
    </td>
  </tr>  
  <tr>
    <td>average</td>
    <td><a href="./src/ext/array/calc.ts">./src/ext/array/calc.ts</a></td>
    <td>Average</td>
    <td>
      数値配列の平均値を取得します。
    </td>
  </tr>  
  <tr>
    <td>max</td>
    <td><a href="./src/ext/array/calc.ts">./src/ext/array/calc.ts</a></td>
    <td>Max</td>
    <td>
      数値配列の最大値を取得します。
    </td>
  </tr>  
  <tr>
    <td>min</td>
    <td><a href="./src/ext/array/calc.ts">./src/ext/array/calc.ts</a></td>
    <td>Min</td>
    <td>
      数値配列の最小値を取得します。
    </td>
  </tr>  

  <tr>
    <td>deepCopy</td>
    <td><a href="./src/ext/array/deep-copy.ts">./src/ext/array/deep-copy.ts</a></td>
    <td>-</td>
    <td>
      Arrayをディープコピーします。
    </td>
  </tr>  

  <tr>
    <td>distinct</td>
    <td><a href="./src/ext/array/distinct.ts">./src/ext/array/distinct.ts</a></td>
    <td>Distinct</td>
    <td>
      配列の重複を除去します。
    </td>
  </tr>  
  <tr>
    <td>distinctBy</td>
    <td><a href="./src/ext/array/distinct.ts">./src/ext/array/distinct.ts</a></td>
    <td>-</td>
    <td>
      判定対象を比較して配列から重複を除去します。
    </td>
  </tr>  


  <tr>
    <td>equalTo</td>
    <td><a href="./src/ext/array/equal-to.ts">./src/ext/array/equal-to.ts</a></td>
    <td>-</td>
    <td>
      配列の内容が同じ場合、true
    </td>
  </tr>  

  <tr>
    <td>first</td>
    <td><a href="./src/ext/array/first.ts">./src/ext/array/first.ts</a></td>
    <td>First</td>
    <td>
      配列の最初のデータを取得します。
    </td>
  </tr>  

  <tr>
    <td>last</td>
    <td><a href="./src/ext/array/last.ts">./src/ext/array/last.ts</a></td>
    <td>Last</td>
    <td>
      配列の最後のデータを取得します。
    </td>
  </tr>  

  <tr>
    <td>orderBy</td>
    <td><a href="./src/ext/array/orderby.ts">./src/ext/array/orderby.ts</a></td>
    <td>-</td>
    <td>
      指定したソート項目を元にソートします。
    </td>
  </tr>  

  <tr>
    <td>selectMany</td>
    <td><a href="./src/ext/array/select-many.ts">./src/ext/array/select-many.ts</a></td>
    <td>SelectMany</td>
    <td>
      callbackfnで戻した値を結合して配列として戻します。
    </td>
  </tr>  

  <tr>
    <td>toLookup</td>
    <td><a href="./src/ext/array/to-lookup.ts">./src/ext/array/to-lookup.ts</a></td>
    <td>ToLookup</td>
    <td>
      配列をMap&lt;K, V[]&gt;に変換します
    </td>
  </tr>  

  <tr>
    <td>toMap</td>
    <td><a href="./src/ext/array/to-map.ts">./src/ext/array/to-map.ts</a></td>
    <td>ToMap</td>
    <td>
      配列をMapに変換します
    </td>
  </tr>  
</table>

## Map

<table>
  <tr>
    <th>Extension Method</th>
    <th>TypeScript file</th>
    <th>Overview</th>
  </tr>
  <tr>
    <td>toArray</td>
    <td><a href="./src/ext/map/to-array.ts">./src/ext/map/to-array.ts</a></td>
    <td>
      Convert Map to an Array.
    </td>
  </tr>  
</table>

## Boolean

<table>
  <tr>
    <th>Extension Method</th>
    <th>TypeScript file</th>
    <th>Overview</th>
  </tr>
  <tr>
    <td>toggle</td>
    <td><a href="./src/ext/boolean/toggle.ts">./src/ext/boolean/toggle.ts</a></td>
    <td>
      Toggle boolean true / false.
    </td>
  </tr>  
</table>


## Object

<table>
  <tr>
    <th>Extension Method</th>
    <th>TypeScript file</th>
    <th>Overview</th>
  </tr>
  <tr>
    <td>deepCopy</td>
    <td><a href="./src/ext/object/deep-copy.ts">./src/ext/object/deep-copy.ts</a></td>
    <td>
      Deep copy the Object.
    </td>
  </tr>  
  <tr>
    <td>equalTo</td>
    <td><a href="./src/ext/object/equal-to.ts">./src/ext/object/equal-to.ts</a></td>
    <td>
      True if the contents of the object are the same.
    </td>
  </tr>  
</table>

