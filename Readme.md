# Micro AWK

AWK for people who don't have time to waste.

## Introduction

AWK is one of my favorite programming languages. It was invented
to be the perfect one-liner language, and it is. It's small, simple,
plays well with others, and gets the job done. Still, there's one
thing that's always bugged me: why does it take so long to write a simple
program? Here's an example:

```awk
BEGIN{print("Hello world!")}
```

The point of AWK is to keep things short and sweet, so why is
"Hello world" so long? Let's shorten it up:

```awk
B{p("Hello world!")}
```

Much better. Now it's perfect for the cryptic one-liners it was built for.
This is just AWK with a few keywords shortened. I hope it helps you out!

## Usage

This is GNU gawk. See any manual for AWK for usage. The only difference is that the following keywords are changed:

old | new
--- | ---
BEGIN | B
END | E
BEGINFILE | BF
ENDFILE | EF
print | p
printf | pf
sprintf | spf
length | len
for | fo
while | w
else | e

Good luck, command line junkies!
