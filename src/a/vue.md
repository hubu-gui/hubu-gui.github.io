# vue
检测是否为外链打开
    toActiveMenuItem(item) {
      if (item.activeUrl.indexOf("http") > -1) {
        window.open(item.activeUrl);
        return;
      }
xxxxx