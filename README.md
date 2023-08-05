# hackintosh-dell-latitude-5480-2017
EFI for Dell Latitude 13" 5480 2017 model. Intel i5-7440HQ 7th Generation. WIP

## Audio
Codec: **ALC3246**/ALC256<br>
Layouts: 0x100002<br>
X 5 - no audio input with builtin mic<br>
X 11 - no audio output from earphones<br>
X 12 - <br>
X 13 - <br>
X 14 - duplicate internal speakers option, one turn to earphone, no audio from earphone<br>
X 16 - no audio output from earphones<br>
17 - almost works, just builtin mic has noise and earphones mic (line-in) option gives no input<br>
X 19 - always internal speakers and nothing works<br>
X 20 - same as 19<br>
21 - same as 17<br>
X 22 - nothing works<br>
X 23 - same as default, always show earphones but not working<br>
X 24 - only Line Out, earphones audio out works, builtin mic works, nothing else<br>
X 28 - only builtin speakers work<br>
33 - same as 17<br>
X 56 - same as 11<br>
X 57 - no audio at all<br>
X 66 - only audio output, no input at all<br>
X 67 - line in and out, only audio out works<br>
X 68 - absolutely no audio in or out, no speakers shown<br>
69 - no builtin speaker out but perfect mic in, only earphone out, not in<br>
Best 70 - all works perfectly, except earphone in<br>
76 - <br>
77 - <br>
88 - <br>
95 - <br>
97 - <br>
99 - <br>
