<?xml version="1.0" encoding="utf-8"?>
<androidx.gridlayout.widget.GridLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:id="@+id/gridLayout"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:columnCount="2"
    android:padding="16dp">

    <Button
        android:id="@+id/btnCall"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_columnWeight="1"
        android:text="Call" />

    <Button
        android:id="@+id/btnWeb"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_columnWeight="1"
        android:text="Open Website" />
</androidx.gridlayout.widget.GridLayout>

