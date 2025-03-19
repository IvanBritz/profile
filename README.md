<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="10dp">

    <!-- BUTTON 1 (Top Left) -->
    <Button
        android:id="@+id/button1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 1"
        android:layout_alignParentStart="true"
        android:layout_margin="5dp"/>

    <!-- BUTTON 2 (Top Right) -->
    <Button
        android:id="@+id/button2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 2"
        android:layout_alignParentEnd="true"
        android:layout_margin="5dp"/>

    <!-- BUTTON 3 (Below BUTTON 1) -->
    <Button
        android:id="@+id/button3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 3"
        android:layout_below="@id/button1"
        android:layout_margin="5dp"/>

    <!-- BUTTON 4 (Right of BUTTON 3) -->
    <Button
        android:id="@+id/button4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 4"
        android:layout_toRightOf="@id/button3"
        android:layout_below="@id/button1"
        android:layout_margin="5dp"/>

    <!-- BUTTON 5 (Right of BUTTON 4) -->
    <Button
        android:id="@+id/button5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 5"
        android:layout_toRightOf="@id/button4"
        android:layout_below="@id/button2"
        android:layout_margin="5dp"/>

    <!-- BUTTON 6 (Below BUTTON 3) -->
    <Button
        android:id="@+id/button6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 6"
        android:layout_below="@id/button3"
        android:layout_margin="5dp"/>

    <!-- BUTTON 7 (Below BUTTON 5) -->
    <Button
        android:id="@+id/button7"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 7"
        android:layout_below="@id/button5"
        android:layout_alignStart="@id/button5"
        android:layout_margin="5dp"/>

    <!-- BUTTON 8 (Below BUTTON 6) -->
    <Button
        android:id="@+id/button8"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 8"
        android:layout_below="@id/button6"
        android:layout_margin="5dp"/>

    <!-- BUTTON 9 (Below BUTTON 7) -->
    <Button
        android:id="@+id/button9"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 9"
        android:layout_below="@id/button7"
        android:layout_alignStart="@id/button7"
        android:layout_margin="5dp"/>

    <!-- BUTTON 10 (Below BUTTON 8) -->
    <Button
        android:id="@+id/button10"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 10"
        android:layout_below="@id/button8"
        android:layout_margin="5dp"/>

    <!-- BUTTON 11 (Below BUTTON 10) -->
    <Button
        android:id="@+id/button11"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 11"
        android:layout_below="@id/button10"
        android:layout_margin="5dp"/>

    <!-- BUTTON 12 (Below BUTTON 11) -->
    <Button
        android:id="@+id/button12"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 12"
        android:layout_below="@id/button11"
        android:layout_margin="5dp"/>

    <!-- BUTTON 13 (Below BUTTON 12) -->
    <Button
        android:id="@+id/button13"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 13"
        android:layout_below="@id/button12"
        android:layout_margin="5dp"/>

    <!-- BUTTON 14 (Below BUTTON 13) -->
    <Button
        android:id="@+id/button14"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 14"
        android:layout_below="@id/button13"
        android:layout_margin="5dp"/>

    <!-- BUTTON 15 (Bottom Right) -->
    <Button
        android:id="@+id/button15"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BUTTON 15"
        android:layout_alignParentBottom="true"
        android:layout_alignParentEnd="true"
        android:layout_margin="5dp"/>
</RelativeLayout>
