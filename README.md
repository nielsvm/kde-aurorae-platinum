# kde-aurorae-platinum

Retro platinum-inspired theme for [KWin](https://en.wikipedia.org/wiki/KWin)'s _aurorae_ theme engine.

![Preview screenshot](./README-1.png)

### Installation
1. `System Settings`> `Application Style`> `Window Decorations`
2. `Get New Window Decorations...`
3. Search "`Platinum`" and hit `Install`, or get it manually [here](https://store.kde.org/p/1319936/).
4. Set `Window border size` to `Normal`.
5. Reorder the titlebar buttons like this:
   ![Preview screenshot](./README-2.png)
6. In case the decoration looks ugly, try flushing caches:
   
   ```
   rm -rf ~/.cache/plasm* ~/.cache/ico* && kwin_x11 --replace&
   ```

---

If you want to go fully _classic_, checkout the full [Look and Feel package](https://github.com/nielsvm/kde-look-and-feel-platinum).
