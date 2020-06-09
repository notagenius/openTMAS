---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Open Lung X-ray Datasets
## COVID-related

|   Index     | Dataset     | Comment  | Size | Resolution | Samples|Link          |
| --------- |:----------:|:----------:|:----------:|:----------:|:----------:| -----:|
|1| Chest Xray Pneumonia      | Normal and Pneumonia  |  2.4GB | >800px |11,742|[https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) | 
|2| Pneumonia Xray Dataset      |  Normal and SARS/MERS/COVID only labelled with Normal and Pneumonia |  88.4M | >1000px |192 |[https://www.kaggle.com/khoongweihao/covid19-xray-dataset-train-test-sets/activity](https://www.kaggle.com/khoongweihao/covid19-xray-dataset-train-test-sets/activity) |
|3| COVID-19 Xray Dataset      |  SARS/MERS/COVID X-ray and CT only labelled with metadata as survial info and description, different views |  182.2 MB | 300px-1000px |250 |[https://github.com/ieee8023/covid-chestxray-dataset](https://github.com/ieee8023/covid-chestxray-dataset) |
|4| COVID-19 CT Dataset      |  NON-COVID/COVID  CT only, with MetaData about patient index and desription | 90 MB | 300px-1500px |346(Covid) + 397(Non-Covid) |[https://github.com/UCSD-AI4H/COVID-CT](https://github.com/UCSD-AI4H/COVID-CT) |
|5| COVID-19 Radiography Database|  Normal/Viral Pneumonia/COVID X-ray only | 1GB | 1024px |219(Covid) + 1341(Normal) + 1345(Pneumonia) |[https://www.kaggle.com/tawsifurrahman/covid19-radiography-database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) |

## General Scope

|   Index     | Dataset     | Comment  | Size | Resolution | Samples|Link          |
| --------- |:----------:|:----------:|:----------:|:----------:|:----------:| -----:|
|1| Pulmonary Chest Xray Abnormalities   | Chest, PNG, X-ray, partly with mask patly not with mask, HD, with seperate txt to state "gender", "age", "normal/abnormal" |  4.1GB | >3000px |139(with mask) + 663(without mask)|[https://www.kaggle.com/kmader/pulmonary-chest-xray-abnormalities](https://www.kaggle.com/kmader/pulmonary-chest-xray-abnormalities) | 
|2| Lung segmentation from Chest X-Ray dataset   | the same with previous dataset but all masked |  9.6GB | >3000px | 346(abnormal) + 358(normal) |[https://www.kaggle.com/nikhilpandey360/chest-xray-masks-and-labels](https://www.kaggle.com/nikhilpandey360/chest-xray-masks-and-labels) | 
|3| MIMIC-CXR Database      | format: MIMIC-CXR and JPG, X-ray |  Credentialed Access | uncheck |377,110 images+ 227,835 studies|[https://physionet.org/content/mimic-cxr/2.0.0/](https://physionet.org/content/mimic-cxr/2.0.0/) | 
|4| NIH Chest X-ray dataset      | format: PNG, X-ray, metadata with view position, gender, height, 50% labeled with findings |  42GB | >1400px |100,000 images|[https://www.kaggle.com/nih-chest-xrays/data](https://www.kaggle.com/nih-chest-xrays/data) | 


### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
