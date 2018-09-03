<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TextView
        android:id="@+id/A_text_view"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:paddingBottom="16dp"
        android:paddingLeft="16dp"
        android:paddingTop="16dp"
        android:text="quantity"
        android:textAllCaps="true"
        android:textSize="16sp" />


    <LinearLayout
        android:id="@+id/Linear"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/A_text_view"
        android:orientation="horizontal">


        <Button
            android:id="@+id/button1"
            android:layout_width="48dp"
            android:layout_height="48dp"
            android:layout_marginBottom="16dp"
            android:layout_marginLeft="16dp"
            android:onClick="decrement"
            android:text="-"
            android:textSize="20sp" />

        <TextView
            android:id="@+id/quantity_text_view"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:paddingBottom="16dp"
            android:paddingLeft="16dp"
            android:text="0"
            android:textColor="#000000"
            android:textSize="16sp" />

        <Button
            android:id="@+id/button2"
            android:layout_width="48dp"
            android:layout_height="48dp"
            android:layout_marginBottom="16dp"
            android:layout_marginLeft="16dp"
            android:onClick="increment"
            android:text="+"
            android:textSize="20sp" />
    </LinearLayout>

    <TextView
        android:id="@+id/Price1_text_view"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/Linear"
        android:paddingBottom="16dp"
        android:paddingLeft="16dp"
        android:text="Price"
        android:textAllCaps="true"
        android:textSize="16sp" />


    <TextView
        android:id="@+id/price_text_view"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/Price1_text_view"
        android:paddingBottom="16dp"
        android:paddingLeft="16dp"
        android:text="0"
        android:textColor="#000000"
        android:textSize="16sp" />


    <Button
        android:id="@+id/button3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/price_text_view"
        android:layout_marginLeft="16sp"
        android:onClick="submitorder"
        android:text="Order"
        android:textAllCaps="true" />





</RelativeLayout>
