# Font-Style
the class name is FontStyle 
you can chang font style by one line !! 
import this class on your project and use it.

package com.example.saedalewaity.product4ever.classes;
import android.content.Context;
import android.graphics.Typeface;
import android.support.v7.app.AppCompatActivity;
import android.view.View;
import android.view.ViewGroup;
import android.widget.Button;
import android.widget.EditText;
import android.widget.TextView;

public class FontStyle<T> extends AppCompatActivity {
    /**
    *set  Font Type
    * one TextView
    **/
    public void setFontType(Context context,String fontName,TextView txt1 ){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),fontName+".ttf");
        txt1.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Two TextView
     **/
    public void  setFontType(Context context ,String fontName, TextView txt1, TextView txt2){
        Typeface tf = Typeface.createFromAsset(getAssets(),
                fontName+".ttf");
        txt1.setTypeface(tf);
        txt2.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Three TextView
     **/
    public void  setFontType(Context context ,String fontName, TextView txt1, TextView txt2, TextView txt3){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        txt1.setTypeface(tf);
        txt2.setTypeface(tf);
        txt3.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Four TextView
     **/
    public void  setFontType(Context context ,String fontName, TextView txt1, TextView txt2, TextView txt3, TextView txt4){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        txt1.setTypeface(tf);
        txt2.setTypeface(tf);
        txt3.setTypeface(tf);
        txt4.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Fife TextView
     **/
    public void  setFontType(Context context ,String fontName, TextView txt1, TextView txt2, TextView txt3, TextView txt4, TextView txt5){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        txt1.setTypeface(tf);
        txt2.setTypeface(tf);
        txt3.setTypeface(tf);
        txt4.setTypeface(tf);
        txt5.setTypeface(tf);
    }
    /**
     *set  Font Type
     * one EditText
     **/
    public void  setFontType(Context context , String fontName, EditText edTxt1){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        edTxt1.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Two EditText
     **/
    public void  setFontType(Context context , String fontName, EditText edTxt1, EditText edTxt2){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        edTxt1.setTypeface(tf);
        edTxt2.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Three EditText
     **/
    public void  setFontType(Context context , String fontName, EditText edTxt1, EditText edTxt2, EditText edTxt3){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        edTxt1.setTypeface(tf);
        edTxt2.setTypeface(tf);
        edTxt3.setTypeface(tf);

    }
    /**
     *set  Font Type
     * Four EditText
     **/
    public void setFontType(Context context , String fontName, EditText edTxt1, EditText edTxt2, EditText edTxt3, EditText edTxt4){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        edTxt1.setTypeface(tf);
        edTxt2.setTypeface(tf);
        edTxt3.setTypeface(tf);
        edTxt4.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Fife EditText
     **/
    public void  setFontType(Context context , String fontName, EditText edTxt1, EditText edTxt2, EditText edTxt3, EditText edTxt4, EditText edTxt5){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        edTxt1.setTypeface(tf);
        edTxt2.setTypeface(tf);
        edTxt3.setTypeface(tf);
        edTxt4.setTypeface(tf);
        edTxt5.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Fife Button
     **/
    public void  setFontType(Context context , String fontName, Button btn1,Button btn2,Button btn3,Button btn4,Button btn5){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        btn1.setTypeface(tf);
        btn2.setTypeface(tf);
        btn3.setTypeface(tf);
        btn4.setTypeface(tf);
        btn5.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Four Button
     **/
    public void  setFontType(Context context , String fontName, Button btn1,Button btn2,Button btn3,Button btn4){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        btn1.setTypeface(tf);
        btn2.setTypeface(tf);
        btn3.setTypeface(tf);
        btn4.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Three Button
     **/
    public void  setFontType(Context context , String fontName, Button btn1,Button btn2,Button btn3){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        btn1.setTypeface(tf);
        btn2.setTypeface(tf);
        btn3.setTypeface(tf);
    }
    /**
     *set  Font Type
     * Two Button
     **/
    public void  setFontType(Context context , String fontName, Button btn1,Button btn2){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        btn1.setTypeface(tf);
        btn2.setTypeface(tf);

    }
    /**
     *set  Font Type
     * one Button
     **/
    public void  setFontType(Context context , String fontName, Button btn1){
        Typeface tf = Typeface.createFromAsset(context.getAssets(),
                fontName+".ttf");
        btn1.setTypeface(tf);
    }

}
