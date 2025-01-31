## 数据分析
###开发者时间分布图
![avatar](./images/whd.png)

上述图统计分析了GitHub上Rust项目日志的时间分布情况，采用打孔图，横轴代表一天中24小时，纵轴代表星期一到星期日，圆点大小代表某时产生的日志数量。
我们可以发现，一天 24 小时中，12:00-22:00 相对活跃，其中，14:00-21:00 最为突出；同时，与我们全域日志时间分布情况相比，18:00-22:00相对更为活跃；周六、周日为休息日，日志数量有所减少。
另一方面，在我们统计了GitHub 上 Apps 的日志时间分布情况时，发现Rust项目几乎没有或者说很少使用机器人。

## 2020年月活跃度与活跃人数变化图
![avatar](./images/act.png)
活跃人数最多达到1854人，活跃度最高达到14741。总体来说，每个月的活跃人数都在1400以上，vscode项目的月活跃人数在4000人左右，相比较Rust项目的活跃人数较少。Rust项目的平均活跃度为12895，从图中可以看出，活跃度相对稳定，在十月份的时候活跃度有个小高峰。

## 2020年Rust项目PR贡献者Top50饼图
![avatar](./images/pie.png)

该饼图展示了Rust项目在2020年中，提交PR最高的50位贡献者每十人一组分成五组后，每组提交PR在所有Top50开发者PR中的占比。一个活跃且健康的开源社区项目，应该是大家一起参与，并且有几位作为领导者，引领项目的发展。显而易见，Rust就是这样优秀的开源项目，Top10的开发者占据了将近一半，但其余几组的开发者也有较高的贡献数。值得一提的是，图上没有展示剩下所有开发者的PR数量，其余所有开发者的PR数量是2300+，也是非常亮眼的数据。

## 2020年Rust开发者相关仓库统计表
| 相关动作数 | 相关仓库 |
| ---- | ---- |
| 123387        | rust-lang/crates.io-index             |
| 69531         | hackerkid/zulip-archive-action-test-2 |
| 58410         | nainardev/tamil-dubbed                |
| 51927         | opentimestamps/nist-inject            |
| 23665         | godotengine/godot                     |
| 22859         | NixOS/nixpkgs                         |
| 22445         | 19h/heartbeat                         |
| 21117         | paritytech/substrate                  |
| 19324         | rust-analyzer/rust-analyzer           |
## 流程分析
