# 第三方材料与许可

本仓库只分发 APK 与说明。第三方组件维持各自许可证，以下许可文件随仓库提供，APK 内亦保留相应通知。

| 材料 | 来源与版本 | 许可文件 |
|---|---|---|
| MDUI | https://github.com/zdhxiong/mdui ，2.1.5 | [MIT](licenses/MDUI-MIT.txt) |
| Leaflet | https://github.com/Leaflet/Leaflet ，1.9.4 | [BSD-2-Clause](licenses/Leaflet-BSD-2-Clause.txt) |
| Leaflet-Geoman Free | https://github.com/geoman-io/leaflet-geoman ，2.18.3 | [MIT](licenses/Geoman-MIT.txt) |
| Leaflet Providers | https://github.com/leaflet-extras/leaflet-providers ，2.0.0 | [BSD-2-Clause](licenses/Leaflet-Providers-BSD-2-Clause.txt) |
| TileLayer Fallback | https://github.com/ghybs/Leaflet.TileLayer.Fallback ，1.0.4 | [Apache-2.0](licenses/Tile-Fallback-Apache-2.0.txt) |
| Turf buffer 及依赖 | https://github.com/Turfjs/turf ，7.2.0 | [许可证集合](licenses/Turf-buffer-dependencies.txt) |
| Bodoni Moda | https://github.com/indestructible-type/Bodoni | [OFL-1.1](licenses/Bodoni-Moda-OFL.txt) |
| coordtransform | https://github.com/wandergis/coordtransform ，本地 Python 移植 | [MIT](licenses/Coordtransform-MIT.txt) |
| gmssl | https://github.com/py-gmssl/py-gmssl ，沿用原工程并含本地兼容修改 | [MIT](licenses/gmssl-MIT.txt) |
| Certifi 根证书 | https://github.com/certifi/python-certifi ，2026.10.23，未修改的数据文件 | [MPL-2.0](licenses/Certifi-MPL-2.0.txt) |

Certifi 对应源材料可从 https://pypi.org/project/certifi/2026.10.23/#files 获取。APK 使用 Python 与 python-for-android 运行环境，随附 [Python 许可](licenses/Python-LICENSE.txt) 与 [python-for-android 许可](licenses/python-for-android-LICENSE.txt)。

在线地图数据不属于上述代码许可：默认影像为 Esri World Imagery，道路底图为 OpenStreetMap，搜索为 Nominatim；界面保留来源署名。使用条件分别由相关服务提供方规定。

公开说明页中的 floral.svg 为本工程原创花卉线描。APK 的百合与花卉位图沿用用户提供的材料，不将这些图片声明为 MIT 或其他第三方库的开源资产；本仓库不另行提供参考海报原图。

2.3.6 内置翡翠湖操场路线为用户明确授权公开分发的手绘路线，仅作为 APK 预设资源；不将路线授权与第三方组件许可证混同。圆圈交互继续使用现有 Leaflet，无新增依赖。

2.3.7 使用 Leaflet 既有 SVG 渲染范围（https://leafletjs.com/reference），不新增依赖。新增离线参考只含翡翠湖历史点位、参考半径和日期，不含历史任务成绩、学号、账户或令牌，且不作为运行协议数据。
