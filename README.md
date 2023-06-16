<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

ئاۋۋال nodejs ، [direnv](https://direnv.net) ، [bun](https://github.com/oven-sh/bun) نى قاچىلاش تەۋسىيە قىلىنىدۇ ، ئاندىن `direnv allow` ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) مۇندەرىجىگە كىرگەندىن كېيىن ئاپتوماتىك ئىجرا بولىدۇ).

مەنىسى: خەنزۇچە ياپونچە ، چاۋشيەنچە ، ئىنگلىزچە ، ئىنگلىزچە باشقا تىللارغا تەرجىمە قىلىنغان. ئەگەر سىز پەقەت خەنزۇچە ۋە ئىنگلىزچە قوللىماقچى بولسىڭىز ، `zh: en` يازسىڭىز بولىدۇ.

## ئالدى كود

* [ئالدى كود](https://github.com/xxai-art/web)
* [تور بېكەت ئۈچۈن تىل بولىقى](https://github.com/xxai-art/web/tree/main/i18n)
* [كىرىش مودۇلى ئۈچۈن تىل بولىقى](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [تور بېكەت كۆپ تىللىق ھۆججەتلەر](https://github.com/xxai-doc)

ئالدى تەرەپتىكى پروگرامما تىلى [@ w5 / coffee_plus](http://npmjs.com/@w5/coffee_plus) بولۇپ ، ئۇ cofeescript گرامماتىكىسىغا ئاساسەن بەزى ئىقتىدارلارنى قوشىدۇ [./coffee_plus.md](./coffee_plus.md) نى كۆرۈڭ.

## تور بېكەت ۋە ھۆججەتلەرنى خەلقئارالاشتۇرۇش

تۆۋەندىكى 3 تۈرگە قۇرۇلۇڭ

* [@ w5 / mdt](https://www.npmjs.com/package/@w5/mdt)

  قوشۇمچىسى `.mdt` ، سىز `<+ ./coffee_plus/import.js>` غا ئوخشاش گرامماتىكىنى ئىشلىتىپ ، سىرتقى ھۆججەتلەرنى كۆرسىتىدۇ ، ھەمدە `.md` قوشۇمچىسى بىلەن بەلگە ھاسىل قىلالايسىز.

* [@ w5 / trmd](https://www.npmjs.com/package/@w5/trmd)

  Markdown تەرجىمىسى كود ۋە ئۇلىنىشلارنى تەرجىمە قىلمايدۇ ھەمدە تەرجىمە قىلىنغان جۈملىلەرنى ساقلايدۇ. ئەگەر تەرجىمە ئۆزگەرتىلگەن ، ئەمما ئەسلى تېكىست ئۆزگەرتىلمىگەن بولسا ، ئۇنى قايتا ئىجرا قىلىش تەرجىمىنىڭ ئۆزگەرتىلىشىنى قاپلىمايدۇ.

* [@ w5 / i18n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` ھاسىل قىلغان تور بېكەتلەرنى تەرجىمە قىلىدىغان تىل ھۆججەتلىرى.

### ھۆججەت تەرجىمىسىنى ئاپتوماتلاشتۇرۇش كۆرسەتمىسى

كود ئامبىرى [xxai-art / doc](https://github.com/xxai-art/doc) نى كۆرۈڭ

ئاۋۋال nodejs ، [direnv](https://direnv.net) ، [bun](https://github.com/oven-sh/bun) نى قاچىلاش تەۋسىيە قىلىنىدۇ ، ئاندىن `direnv allow` ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) مۇندەرىجىگە كىرگەندىن كېيىن ئاپتوماتىك ئىجرا بولىدۇ).

يۈزلىگەن تىلغا تەرجىمە قىلىنغان چوڭ كود بازىسىدىن ساقلىنىش ئۈچۈن ، مەن ھەر بىر تىل ئۈچۈن ئايرىم كود بازىسى قۇرۇپ ، كود بازىسىنى ساقلايدىغان تەشكىلات قۇردىم.

مۇھىت ئۆزگەرگۈچى مىقدار `GITHUB_ACCESS_TOKEN` نى تەڭشەپ ئاندىن [create.github.coffee نى](https://github.com/xxai-art/doc/blob/main/create.github.coffee) ئىجرا قىلسىڭىز ئاپتوماتىك ھالدا كود ئامبىرى قۇرىدۇ.

ئەلۋەتتە ، ئۇنى كود ئاساسىغا قويسىڭىزمۇ بولىدۇ.

تەرجىمە قوليازما پايدىلىنىش [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

قوليازما كودى تۆۋەندىكىدەك ئىزاھلىنىدۇ:

[bunx](https://bun.sh/docs/cli/bunx) تېزرەك npx نىڭ ئورنىنى ئالىدۇ. ئەلۋەتتە ، ئەگەر سىزدە بولكا ئورنىتىلمىغان بولسا ، ئۇنىڭ ئورنىغا `npx` ئىشلەتسىڭىز بولىدۇ.

`bunx mdt zh` `.mdt` zh مۇندەرىجىسىدە `.md` قىلىپ كۆرسىتىدۇ ، تۆۋەندىكى 2 ئۇلانغان ھۆججەتنى كۆرۈڭ

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` تەرجىمىنىڭ يادرولۇق كودى (ئەگەر سىزدە پەقەت `nodejs` قاچىلانغان ، ئەمما `bun` ۋە `direnv` ئورنىتىلمىغان بولسا ، `npx i18n` نى تەرجىمە قىلسىڭىزمۇ بولىدۇ).

ئۇ [i18n.yml نى](https://github.com/xxai-art/doc/blob/main/i18n.yml) تەھلىل قىلىدۇ ، بۇ ھۆججەتتىكى `i18n.yml` نىڭ سەپلىمىسى تۆۋەندىكىچە:

```
en:
zh: ja ko en
```

مەنىسى: خەنزۇچە ياپونچە ، چاۋشيەنچە ، ئىنگلىزچە ، ئىنگلىزچە باشقا تىللارغا تەرجىمە قىلىنغان. ئەگەر سىز پەقەت خەنزۇچە ۋە ئىنگلىزچە قوللىماقچى بولسىڭىز ، `zh: en` يازسىڭىز بولىدۇ.

`README.md` ئاخىرقىسى [gen](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) `README.md` بۇ كود ناھايىتى ئاددىي ، ئۇنى ئۆزىڭىز كۆرەلەيسىز.

Google API ھەقسىز تەرجىمە ئۈچۈن ئىشلىتىلىدۇ. ئەگەر گۇگۇلنى زىيارەت قىلالمىسىڭىز ۋاكالەتچى سەپلەڭ ۋە ۋاكالەتچى قويۇڭ ، مەسىلەن:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

تەرجىمە قوليازمىسى `.i18n` مۇندەرىجىسىدە تەرجىمە قىلىنغان غەملەك ھاسىل قىلىدۇ ، ئۇنى `git status` بىلەن تەكشۈرۈپ ، كود ئامبىرىغا قوشۇپ قايتا-قايتا تەرجىمە قىلىشتىن ساقلىنىڭ.

غەملەكنى يېڭىلاش ئۈچۈن ھەر قېتىم تەرجىمىنى ئۆزگەرتكەندە `bunx i18n` نى ئىجرا قىلىڭ.

ئەگەر ئەسلى تېكىست بىلەن تەرجىمە بىرلا ۋاقىتتا ئۆزگەرتىلسە ، غەملەك قالايمىقانلىشىدۇ ، شۇڭا ئۆزگەرتمەكچى بولسىڭىز ، پەقەت بىرنىلا ئۆزگەرتەلەيسىز ، ئاندىن `bunx i18n` ئىجرا قىلىپ ، ساقلىغۇچنى يېڭىلايسىز.
