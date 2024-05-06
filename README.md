## Project description

The main file used in the project is `index.qmd`. This project counted metadiscourse markers according to Sicheng Wang's categorization based on the selected text `Control of the activity of CAR-T cells within tumours via focused ultrasound` and its translation. The main purpose is to test the biomedical literature translation methods for lay person by comparing the number of metadiscourse markers in the source text and its translation. The derived data files are stored in the `data/derived` which includes the texts in ST and TT, metadiscourse numbers in ST and TT and dataset for inferential analysis. The categorization includes:

**English**

1. Hedges: "may", "typically", "relatively", "slightly", "probably" and "suggest"
2. Boosters: "especially", "substantially", "significantly", "dramatically", "precisely", "merely", "particularly", "in particular", "very", "without any", "demonstrate", "indicate" and "verify"
3. Attitude markers: "difficult", and "significant"
4. Engagement markers: "given"
5. Self-mentions: "we" and "our"
6. Transitions: "however", "while", "but", "thus", "in contrast(to)", "additionally", "moreover", "also", "still", "therefore", "as such" and "and"
7. Frame markers: "first", "then", "further", "recently", "here" and "taken together"
8. Endodphoric markers: "Fig", "Video", "Methods", and "as described above"
9. Code glosses: "for instance" and "including"

**Chinese**

1. Hedges: "一定程度", "可能", "几乎", "可以说是", "略有"
2. Boosters: "不会", "无法", "不再", "无需", "不对", "均不", "更是", "必需", "就能", "任何", "大大", "尤其", "只有", "仅", "最", "极", "明显", "显著", "证实", "揭示", "证明", "验证", "不存在"
3. Attitude markers: "有望", "难"
4. Engagement markers: "说明"
5. Self-mentions: "我们"
6. Transitions: "但", "然而", "而", "虽然", "但是", "且", "从而", "如此", "由于", "这样一来", "因为", "所以", "因此", "随后", "如果", "若", "或", "同时", "以及", "仍", "和", "也", "相比", "并"
7. Frame markers: "首先", "先是", "第一次/第二次", "这是", "第一部分/第二部分", "进一步"
8. Endodphoric markers: "见图", "如图", "补充数据图", "附录图", "技术原理部分", "方案", "附录视频", "上述", "先前"
9. Code glosses: "即", "该", "其中", "包括"

## Instructions

Running the `index.qmd` to review the project in html. Datasets could be found in `data`, data preparation process could be seen in `process`, more information about presentation could be seen in `reports/slides/workshop/index.qmd`.
