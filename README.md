# vuex-plugins-loading
你在任何地方都不需要写showLoading 和hideLoading。值得拥有的vuex-plugins-loading。
## 安装
 npm i vuex-plugins-loading -S

## 组件中调用
```
### namespace: home

### actions: initPage

...mapState({
      loading: state => state['@@loading'].effects['namespace/actions']
    }),
```