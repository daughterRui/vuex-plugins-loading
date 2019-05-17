# vuex-plugins-loading
你在任何地方都不需要写showLoading 和hideLoading。值得拥有的vuex-plugins-loading。
## Install
```
 npm i vuex-plugins-loading -S
```

## Usage
```
import createLoadingPlugin from 'vuex-plugins-loading'

Vue.use(Vuex)

export default new Vuex.Store({

  plugins: [createLoadingPlugin()]

})
```

```
### namespace: home

### actions: initPage

...mapState({
      loading: state => state['@@loading'].effects['namespace/actions']
    }),
```
## 注意
> 安装此插件vuex版本必需在3.1.0