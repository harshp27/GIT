����   4 N  Advanced/Plaintiff1  java/lang/Object <init> ()V Code
  	   LineNumberTable LocalVariableTable this LAdvanced/Plaintiff1; main ([Ljava/lang/String;)V 
Exceptions  java/lang/InterruptedException  webdriver.chrome.driver  ./driver/chromedriver.exe
    java/lang/System   setProperty 8(Ljava/lang/String;Ljava/lang/String;)Ljava/lang/String;  'org/openqa/selenium/chrome/ChromeDriver
  	 ! .https://www.accessibility.com/digital-lawsuits # % $ org/openqa/selenium/WebDriver & ' get (Ljava/lang/String;)V ) hs-eu-confirmation-button
 + - , org/openqa/selenium/By . / id ,(Ljava/lang/String;)Lorg/openqa/selenium/By; # 1 2 3 findElement :(Lorg/openqa/selenium/By;)Lorg/openqa/selenium/WebElement; 5 7 6 org/openqa/selenium/WebElement 8  click : (ANDREW TORO v. Atwood Distributing, L.P.
 + < = / linkText ? %BRAULIO THORNE v. LIPSCOMB UNIVERSITY A *BRAULIO THORNE v. UNIVERSITY OF EVANSVILLE C %BRAULIO THORNE v. UNIVERSITY OF MIAMI E .JAMES WATSON v. OFFERDAHL'S OFF-THE-GRILL INC. G #ANDREW TORO v. Awesome Diecast, LLC args [Ljava/lang/String; driver Lorg/openqa/selenium/WebDriver; 
SourceFile Plaintiff1.java !               /     *� �    
                    	             �     �� W� Y� L+ � " +(� *� 0 � 4 +9� ;� 0 � 4 +>� ;� 0 � 4 +@� ;� 0 � 4 +B� ;� 0 � 4 +D� ;� 0 � 4 +F� ;� 0 � 4 �    
   .    
       (  8  H  X  h  x  �         � H I    y J K   L    M