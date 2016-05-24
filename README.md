# Ripple <br>
## Step-1   Add Dependency on build.gradle(Module:app)<br>
dependencies {
  compile 'com.github.PatelMilan/riplle:csiw:1.0.0'
}
## Step-2 Put the your widget bellow tags
<br>
Exp:-<br>
&lt;com.csiw.Ripple<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  android:layout_width="match_parent"<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;android:layout_height="match_parent"<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;view_centered="true"<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;view_type="doubleRipple"<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;view_color="@color/rippelColors"&gt;<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;Button<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;android:layout_width="match_parent"<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;android:layout_height="match_parent"<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;android:text="Ripple Demo"/&gt;<br><br>
&lt;/com.csiw.Ripple&gt;
