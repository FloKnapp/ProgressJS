# ProgressJS
Small yet powerful javascript library for radial progress bars

### Usage
```
<script src="/progress.js"></script>

<div class="progress-js"></div>

```

#### Further configuration
```
<script src="/progress.js"></script>

<!-- Render progress with predefined value of 70 percent -->
<div class="progress-js" data-value="70"></div>

<!-- Render progress with partly calculation -->
<div class="progress-js" data-current="10" data-overall="100"></div>

<!-- Render progress with partly calculation and custom foreground and background color -->
<div class="progress-js" data-current="10" data-overall="100" data-fgcolor="gray" data-bgcolor="black"></div>
```

Possible configuration attributes:

- value
- current
- overall
- width
- height
- strokeWidth
- fgColor
- bgColor
- duration
- fontFamily
- fontSize
- label
- counter

### Notes

You can use ```value``` only if ```current``` and ```overall``` aren't set and vice versa.
