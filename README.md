# RadarView
仿绝地求生小黑盒雷达图

## 效果图

![](http://m.qpic.cn/psb?/V14Ej48r2rOT1E/gbNtHO50x6A8bb9eKnm3Yy4LaxJRPAe4MqOzlhMyCX0!/b/dDYBAAAAAAAA&bo=0AKgBQAAAAADB1U!&rf=viewer_4)

## 简单使用

      <com.xx.radar.RadarView
            app:maxValue="100"
            app:valueColor="@color/radarValueColor"
            app:lineColor="@color/gray_line"
            app:radarValueSize="15sp"
            app:radarDescSize="8sp"
            android:layout_width="match_parent"
            android:layout_height="match_parent" />
            
## 自定义属性说明
|属性|属性说明|类型|默认值|
|:--:|:--:|:--:|:--:|
|maxValue|每个属性的最大值|float|100f|
|valueColor|对应的选中区域块|color|0x992067a4|
|lineColor|雷达图的线条|color|0xffededed|
|radarValueSize|雷达图每个属性的值text文字大小|dimension|15sp|
|radarDescSize|雷达图每个属性的描述text文字大小|dimension|8sp|
|radarTextMargin|雷达图的文字与图的边距|integer|5dp|
