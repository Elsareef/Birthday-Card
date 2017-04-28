# Birthday-Card
#it is my first thing doing in Android i still a student right now with udacity 



<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.mostafa.myapplication.MainActivity">

        <ImageView
            android:id="@+id/imageView"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:scaleType="centerCrop"
            app:srcCompat="@drawable/androidbirthday"
            android:layout_alignParentTop="true"
            android:layout_alignParentStart="true" />

        <TextView
            android:id="@+id/textView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignParentTop="true"

            android:fontFamily="sans-serif-Light"
            android:paddingLeft="20dp"
            android:paddingTop="20dp"
            android:text="Happy Birthday Universe"
            android:textColor="#FAFAFA"
            android:textSize="20sp"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/textView2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignParentBottom="true"
            android:layout_alignParentEnd="true"
            android:padding="20dp"
            android:paddingBottom="20dp"
            android:text="From Mostafa"
            android:textColor="#FAFAFA"
            android:fontFamily="sans-serif-Light"
            android:textSize="18sp"
            android:textStyle="bold|italic" />
</RelativeLayout>
