# Image Compression Java Application

This is a simple Java application that compresses images. It uses the Thumbnails library to scale and reduce the quality of images, thereby compressing them.

## Usage

The main method of the application takes two arguments: the input path and the output path. The input path is the location of the image you want to compress, and the output path is where the compressed image will be saved.

```java
compressImage(Path inputPath, Path outputPath)
```

## Dependencies

This project uses the Thumbnails library for image compression. Make sure to include it in your project dependencies.

## Error Handling

In case of any errors during the compression process, the application will print an error message to the console.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

