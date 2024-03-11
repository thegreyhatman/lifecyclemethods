# Ex.No:2 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
package com.example.mad3;

import android.content.Intent;
import android.os.Bundle;
import android.util.Log;
import android.widget.Toast;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.d("Activity_Lifecycle","onCreate invoked");
        Toast.makeText(MainActivity.this,"Created",Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onStart() {
        super.onStart();
        Log.d("Activity_Lifecycle","onStart invoked");
        Toast.makeText(MainActivity.this,"Start",Toast.LENGTH_SHORT).show();
    }
    @Override
    protected void onResume() {
        super.onResume();
        Log.d("Activity_Lifecycle","onResume invoked");
        Toast.makeText(MainActivity.this,"Resume",Toast.LENGTH_SHORT).show();
    }
    @Override
    protected void onPause() {
        super.onPause();
        Log.d("Activity_Lifecycle","onPause invoked");
        Toast.makeText(MainActivity.this,"Pause",Toast.LENGTH_SHORT).show();
    }
    @Override
    protected void onStop() {
        super.onStop();
        Log.d("Activity_Lifecycle","onStop invoked");
        Toast.makeText(MainActivity.this,"Stop",Toast.LENGTH_SHORT).show();
    }
    @Override
    protected void onRestart() {
        super.onRestart();
        Log.d("Activity_Lifecycle","onRestart invoked");
        Toast.makeText(MainActivity.this,"Restart",Toast.LENGTH_SHORT).show();
    }
    @Override
    protected void onDestroy() {
        super.onDestroy();
        Log.d("Activity_Lifecycle","onDestroy invoked");
        Toast.makeText(MainActivity.this,"Destroy",Toast.LENGTH_SHORT).show();
    }



}
Developed by:
Registeration Number : 212221040039
*/
```

## OUTPUT
![WhatsApp Image 2024-03-11 at 09 22 56_5f06488e](https://github.com/thegreyhatman/lifecyclemethods/assets/136783487/e440abd9-4c03-4a14-9c5b-83be6b68565d)




## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
