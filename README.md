# jsp_4

![image](https://user-images.githubusercontent.com/37132897/158108384-a8034e12-3029-4eef-ac5f-df745b885ad3.png)

- x가 y보다 크냐 : x(3) > y(5), false 출력
- x가 y보다 크거나 같냐 : x(3) >= y(5), false 출력
- y가 x보다 크냐 : x(3) < y(5), true 출력
- y가 x보다 크거나 같냐 : x(3) <= y(5), true 출력
- x와 z가 값이 같냐, 타입은 달라도 됨 : x == z, true 출력
- x와 y가 값이 다르냐 : x != y, true 출력
- x와 z가 값과 타입까지 같냐 : x===z, false 출력

      // 변수
      
      var x, y, z;
      
      x = 3;
      
      y = 5;
      
      z = "3";
      
      // 변수 이용한 비교 연산자
      
      document.write("1: ", x > y);
      
      document.write("<br>");
      
      document.write("2: ", x >= y);
      
      document.write("<br>");
      
      document.write("3: ", x < y);
      
      document.write("<br>");
      
      document.write("4: ", x <= y);
      
      document.write("<br>");
      
      document.write("5: ", x == z); // =가 2개일때는, 내용(값)만 같으면 된다.
      
      document.write("<br>");
      
      document.write("6: ", x != y);
      
      document.write("<br>");
      
      document.write("7: ", x === z); // =가 3개일때는, 내용에 type 까지 같은  본다.
      
      document.write("<br>");
