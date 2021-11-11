# -
Activity.xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:gravity="center"
    android:padding="10dp"
    android:orientation="vertical"
    tools:context=".MainActivity">
        <TextView
            android:id="@+id/tv_1"
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:text="助农助销"
            android:textColor="#8f1206"
            android:textSize="20dp"
            android:gravity="center"
            />
    <ImageView
        android:id="@+id/I_1"
        android:layout_width="500dp"
        android:layout_height="250dp"
        android:src="@drawable/zhuc"
        ></ImageView>

    <LinearLayout
        android:layout_width="373dp"
        android:layout_height="48dp"
        android:orientation="horizontal">

        <EditText
            android:id="@+id/ex_1"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:ems="10"
            android:hint="帐号"
            android:inputType="textPersonName" />

    </LinearLayout>
    <LinearLayout
        android:layout_width="373dp"
        android:layout_height="48dp"
        android:orientation="horizontal">

        <EditText
            android:id="@+id/ex_2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:ems="10"
            android:hint="密码"
            android:inputType="textPersonName" />

    </LinearLayout>

    <Button
        android:id="@+id/b_1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"

        android:text="登录" />

    <Button
        android:id="@+id/b_2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="注册" />


</LinearLayout>


login.xml

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">
    <TextView
        android:id="@+id/register_surface"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="用户注册"
        android:textSize="40dp"
        android:background="#00FF00"
        android:layout_gravity="center"
        />
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <TextView
            android:id="@+id/identity_text"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="账号"
            android:textSize="30dp"
            android:layout_marginLeft="30dp"
            android:layout_marginTop="50dp"/>

        <EditText
            android:id="@+id/input_identity_text"
            android:layout_width="250dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="5dp"
            android:textSize="30dp"
            android:maxLines="1"
            android:hint="******"
            android:layout_marginTop="50dp"/>



    </LinearLayout>
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/password_text"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="密码"
            android:textSize="30dp"
            android:layout_marginLeft="30dp"/>

        <EditText
            android:id="@+id/input_password_text"
            android:layout_width="250dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="5dp"
            android:textSize="30dp"
            android:maxLines="1"
            android:hint="******"/>
    </LinearLayout>

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/mailbox_text"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="邮箱"
            android:textSize="30dp"
            android:layout_marginLeft="30dp"/>

        <EditText
            android:id="@+id/input_mailbox_text"
            android:layout_width="250dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="5dp"
            android:textSize="30dp"
            android:maxLines="1"
            android:hint="******"/>
    </LinearLayout>

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/phonenumber_text"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="电话"
            android:textSize="30dp"
            android:layout_marginLeft="30dp"/>

        <EditText
            android:id="@+id/input_phonenumber_text"
            android:layout_width="250dp"
            android:layout_height="wrap_content"
            android:layout_marginLeft="5dp"
            android:textSize="30dp"
            android:maxLines="1"
            android:hint="******"/>
    </LinearLayout>
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <Button
            android:id="@+id/surface2_register_button"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="25dp"
            android:background="#00FF00"
            android:layout_marginLeft="150dp"
            android:layout_marginTop="20dp"
            android:text="注册"
            />

    </LinearLayout>

</LinearLayout>



还有一些不会求指教，做一个购物APP
