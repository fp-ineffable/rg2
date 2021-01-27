
[G2Plot 2.0 Upgrade guide](https://g2plot.antv.vision/en/docs/manual/upgrade/)


## Abandoned charts

- [x] g2Bubble                 ->  g2Scatter
- [x] g2StackedColumn          ->  g2Column
- [x] g2GroupedColumn          ->  g2Column
- [x] g2PercentStackedColumn   ->  g2Column
- [x] g2RangeColumn            ->  g2Column
- [x] g2StackedBar             ->  g2Bar
- [x] g2PercentStackedBar      ->  g2Bar
- [x] g2RangeBar               ->  g2Bar
- [x] g2Donut                  ->  g2Pie
- [x] g2DualLine               ->  g2Demos
- [x] g2ColumnLine             ->  g2Demos
- [x] g2StackedColumnLine      ->  g2Demos
- [x] g2GroupedColumnLine      ->  g2Demos
- [x] g2StackedArea            ->  g2Area
- [x] g2PercentStackedArea     ->  g2Area
- [x] g2StepLine               ->  g2Line


## Configuration change

G2Plot 2.0 is compatible with most of the chart functions and configuration items of version 1.x. The details are as follows:

### General attributes

- [x] title        deprecated
- [x] description  deprecated
- [x] forceFit     deprecated, use `autoFit` instead
- [x] responsive   deprecated, built-in
- [x] guideLine    deprecated，use `annotations` instead
- [ ] label	       label.type may has compatibility issues, if the error is reported, modify/remove the type configuration
- [ ] slider	       Syntax change
- [ ] scrollbar	   Syntax change
- [ ] events	       Syntax change
- [ ] visible   	   Syntax change
- [ ] animation	   Syntax change


## Private configuration

- [x] Scatter
- [x] Rose
- [x] Bullet
- [x] WordCloud
- [x] Gauge
- [x] Liquid
- [x] Radar
- [x] TinyArea, TinyColumn, TinyLine





