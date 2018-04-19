# https-image-downloader
Java image downloader and placer in ImageView

Using : 

Add ImageView.java file to your Android Project

Example : 

```java
  ImageView yourImageView = (ImageView) findViewById(R.id.image_view);
  new ImageDownloader(yourImageView).execute(yourHttpsUrl);
```

Note : this class trusts all https links
