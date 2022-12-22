# intro

`SceneSetup.intro();`

# intro-play-button

(...51)

[MAIN!](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: Jadi sebelum kita mula, bagaimanakah hendak *kamu* membaca?

`publish("show_options_bottom")`

# intro-start-2

n3: Sekarang, mari kita mulakan cerita kita...

```
publish("hide_tabs");
clearText();
```

(...1000)

`publish("intro-to-game-2")`

n2: INI ADALAH SEORANG MANUSIA

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

```
SceneSetup.act1();
publish("hide_tabs");
music('battle', {volume:0.5});
```

(...300)

n: DAN INI ADALAH KEGELISAHAN MANUSIA

n: _KAMU_ ADALAH SI KEGELISAHAN ITU

(#act1_normal)


# act1_normal

```
hong({body:"putaway"});
sfx("rustle");
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Tidak. Tak, tidak akan, tidak mahu mendengar. Akan aku periksa telefon pintarku.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: KERJA ANDA ADALAH UNTUK MELINDUNGI MANUSIA-MU DARI SEBARANG *BAHAYA*

`bb({eyes:"look", mouth:"small_lock", body:"fear"})`

b: *Tercungap*! Kamu sedang menatal hidup kamu di Twitter! Lagi!

```
bb({eyes:"normal", mouth:"normal", body:"normal"});
hong({eyes:"annoyed"});
```

h: Ya saya terfikirkan kenapa tidak saya duduk dan lebih menumpukan kepada pemikiran saya lebih kerap.

`hong({eyes:"neutral"});`

n: CEPAT, PERINGATKAN MEREKA FASAL *BAHAYA!*

```
bb({eyes:"look"});
```

[Alamak, lihat pada berita yang teruk itu!](#act1d_news)

[Alamak, adakah *tweet* itu secara rahsianya tentang *kita?*](#act1d_subtweet)

[Hey, ada GIF fasal kucing sedang meminum susu](#act1d_milk)

# act1d_milk

`hong({mouth:"smile", eyes:"surprise"});`

h: Heh ya itu comel, saya--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: KUCING TIDAK BERKEMAMPUAN UNTUK MENCERNA SUSU DAN KITA ADALAH ORANG YANG TERUK KERANA MENIKMATI PENDERAAN HAIWAN

(...200)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("20p", "bad");
publish("hp_show");
```



