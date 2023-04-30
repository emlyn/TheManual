# Chapter 5 - Recreating the beep synth

## Compile errors

If you get the error ending in:

```supercollider
^^ The preceding error dump is for ERROR: Primitive '_FilePutString' failed.
Failed.
RECEIVER: a File
```

You didn't edit the file name in the synth def and it can't save the compiled output

```supercollider
}).writeDefFile("/Users/gordonguthrie/.synthdefs"))
```