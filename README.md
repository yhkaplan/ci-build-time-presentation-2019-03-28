slidenumbers: true

# [fit] Speeding up your CI

---

# Self Intro

- Joshua Kaplan
- minne @ GMO Pepabo
- Danger-Swift contributer
- Likes 🤖

^ 日本最大のハンドメイドマーケットプレイスである minne の iOS エンジニア
本日発表する Danger の contributer
機械に仕事をしてもらうのが好き

---

# [fit] What do we use CI for?

---

1. Automated testing
2. Static analysis (linting etc)
3. Beta deployment
4. Release build deployment

---

# [fit] What were build times like?

---

- 1st build: 55 minutes
- 2nd and later: 35 minutes

---

# [fit] What did they become?

---

- 14-16 minutes

---

# [fit] How?

---

# [fit] Caching frameworks

---

- Using [Rome](https://github.com/blender/Rome)
- Biggest impact: 55 to 33 minutes

---

# [fit] Upgrading plan

---

< Photo

---

- Not much to explain here
- 33 to 20 minutes

---

# [fit] Only getting code coverage when tests change

---

- 2 minutes less

---

# [fit] Remove pointless indexing

---

< Photo

- https://twitter.com/i/web/status/1100404024224804871

---

- Saves 1 or 2 minutes

```sh
COMPILER_INDEX_STORE_ENABLE=NO
```

---

# [fit] Other techniques I look forward to

---

- Parallelization
- Separate modules

---

# [fit] Conclusion

---

# [fit] Mess around
