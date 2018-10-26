# StringStyleBuilder

Easy to use SpannableStringBuilder for Android. Simply insert `StringStyleBuilder.java` file to anywhere in your project and use it like this:
```java
StringStyleBuilder stringStyleBuilder = new StringStyleBuilder()
                          .addRegular("Regular text with some ")
                          .addBold("BOLD TEXT ")
                          .addRegular("then some regular again or you might want to ")
                          .addLink("click this line to go to my github", "https://guthub.com/koceeng");
yourTextView.setText(stringStyleBuilder.get(), TextView.BufferType.SPANNABLE);
```
