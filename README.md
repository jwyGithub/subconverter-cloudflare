# subconverter-cloudflare

subconverter-cloudflare

## 演示网站

[https://sub-convert.visitor-worker.workers.dev/](https://sub-convert.visitor-worker.workers.dev/)

## 环境变量

<table>
  <tr>
    <td>变量名</td>
    <td>说明</td>
    <td>变量值</td>
  </tr>
  <tr>
    <td>BACKEND</td>
    <td>后端转换地址</td>
    <td></td>
  </tr>
  <tr>
    <td>SUB_BUCKET</td>
    <td>KV名</td>
    <td></td>
  </tr>
  <tr>
    <td>LOCK_BACKEND</td>
    <td>是否禁用后端地址选择</td>
    <td>默认true</td>
  </tr>
  <tr>
    <td>FRONTEND</td>
    <td>页面地址</td>
    <td>https://raw.githubusercontent.com/jwyGithub/subconverter-cloudflare/main/index.html</td>
  </tr>
  <tr>
    <td>REMOTE_CONFIG</td>
    <td>自定义远端配置,多个换行</td>
    <td>
        自定义配置1: https://xxxxx1 <br>
        自定义配置2: https://xxxxx2
    </td>
  </tr>
</table>

### 鸣谢

-   [https://github.com/bulianglin/psub](https://github.com/bulianglin/psub)
-   [https://github.com/ACL4SSR/ACL4SSRs](https://github.com/ACL4SSR/ACL4SSR)
