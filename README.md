Generating a test redirect URL for testing the development environment — **for research and testing purposes only!**

**Endpoint**
```

https://click.tub3.net/M03y1MT6?

```

**Params**
```

sub_id1 -- is reserved and will contain the unique visit ID 
sub_id2-sub_id9 -- can be used for additional params 
sub_id10 -- used to redirect to url

```

**Example** 
```

sub_id2 = test
sub_id10 = google.com
The sharable result should be like this:
https://click.tub3.net/M03y1MT6?sub_id2=test&sub_id10=google.com

```

---

### How to encode URL?

#### Online tools:

- [urlencoder.org](https://www.urlencoder.org/)
    
- [urldecoder.io](https://www.urldecoder.io/)
    

#### In JS:

```

encodeURIComponent("https://google.com") // returns: "https%3A%2F%2Fgoogle.com"

```
