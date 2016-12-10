# android-close-pixelate

This is the android port of https://github.com/desandro/close-pixelate.

[**close-pixelate.desandro.com**](http://close-pixelate.desandro.com)

## Examples

![Officer](screenshots/officer.jpg?raw=true)

```
ClosePixelate.render(bitmap,
        new Options.Builder(Shape.Diamond)
                .setResolution(48)
                .setSize(50)
                .build(),
        new Options.Builder(Shape.Diamond)
                .setResolution(48)
                .setOffset(24)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(8)
                .setSize(6)
                .build());
```

![Stanley](screenshots/stanley.jpg?raw=true)

```
ClosePixelate.render(bitmap,
        new Options.Builder(Shape.Square)
                .setResolution(32)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(32)
                .setOffset(15)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(32)
                .setSize(26)
                .setOffset(13)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(32)
                .setSize(18)
                .setOffset(10)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(32)
                .setSize(12)
                .setOffset(8)
                .build());
```

![Take my portrait](screenshots/take-my-portrait.jpg?raw=true)

```
ClosePixelate.render(bitmap,
        new Options.Builder(Shape.Square)
                .setResolution(48)
                .build(),
        new Options.Builder(Shape.Diamond)
                .setResolution(48)
                .setOffset(12)
                .setAlpha(0.5f)
                .build(),
        new Options.Builder(Shape.Diamond)
                .setResolution(48)
                .setOffset(36)
                .setAlpha(0.5f)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(16)
                .setSize(8)
                .setOffset(4)
                .build());
```

![Tony](screenshots/tony.jpg?raw=true)

```
ClosePixelate.render(bitmap,
        new Options.Builder(Shape.Circle)
                .setResolution(32)
                .setSize(6)
                .setOffset(8)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(32)
                .setSize(9)
                .setOffset(16)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(32)
                .setSize(12)
                .setOffset(24)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(32)
                .setSize(9)
                .setOffset(0)
                .build());
```

![Wonder](screenshots/wonder.jpg?raw=true)

```
ClosePixelate.render(bitmap,
        new Options.Builder(Shape.Diamond)
                .setResolution(24)
                .setSize(25)
                .build(),
        new Options.Builder(Shape.Diamond)
                .setResolution(24)
                .setOffset(12)
                .build(),
        new Options.Builder(Shape.Square)
                .setResolution(24)
                .setAlpha(0.6f)
                .build());
```

![Anita](screenshots/anita.jpg?raw=true)

```
ClosePixelate.render(bitmap,
        new Options.Builder(Shape.Square)
                .setResolution(32)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(32)
                .setOffset(16)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(32)
                .setOffset(0)
                .setAlpha(0.5f)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(16)
                .setSize(9)
                .setOffset(0)
                .setAlpha(0.5f)
                .build());
```

![Giraffe](screenshots/giraffe.jpg?raw=true)

```
ClosePixelate.render(bitmap,
        new Options.Builder(Shape.Circle)
                .setResolution(24)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(24)
                .setSize(9)
                .setOffset(12)
                .build());
```

![Kendra](screenshots/kendra.jpg?raw=true)

```
ClosePixelate.render(bitmap,
        new Options.Builder(Shape.Square)
                .setResolution(48)
                .setOffset(24)
                .build(),
        new Options.Builder(Shape.Circle)
                .setResolution(48)
                .setOffset(0)
                .build(),
        new Options.Builder(Shape.Diamond)
                .setResolution(16)
                .setSize(15)
                .setOffset(0)
                .setAlpha(0.6f)
                .build(),
        new Options.Builder(Shape.Diamond)
                .setResolution(16)
                .setSize(15)
                .setOffset(8)
                .setAlpha(0.6f)
                .build());
```

![Gavin](screenshots/gavin.jpg?raw=true)

```
ClosePixelate.render(bitmap,
        new Options.Builder(Shape.Square)
                .setResolution(48)
                .build(),
        new Options.Builder(Shape.Diamond)
                .setResolution(12)
                .setSize(8)
                .build(),
        new Options.Builder(Shape.Diamond)
                .setResolution(12)
                .setSize(8)
                .setOffset(6)
                .build());
```
