# viral-bacterial-pneumonia-classification
Repository for pneumonia classification
# Model
The models that had been used:
* Simple CNN
* InceptionResNetV2
* DenseNet201
# Dataset
Dataset that had been used is taken from https://www.kaggle.com/wilhelmberghammer/chest-xrays-pneumonia-detection/version/1 <br/>
Total images contained in the dataset are 4448 images

<table>
    <thead>
        <tr>
            <th>Dataset</th>
            <th>Label</th>
            <th>Images</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=3>Train</td>
            <td>Normal</td>
            <td>1104</td>
        </tr>
        <tr>
            <td>Bacterial</td>
            <td rowspan=2>1108</td>
        </tr>
        <tr>
            <td>Viral</td>
        </tr>
        <tr>
            <td rowspan=3>Validation</td>
            <td>Normal</td>
            <td rowspan=3>276</td>
        </tr>
        <tr>
            <td>Bacterial</td>
        </tr>
        <tr>
            <td>Viral</td>
        </tr>
        <tr>
            <td rowspan=3>Test</td>
            <td>Normal</td>
            <td rowspan=3>100</td>
        </tr>
        <tr>
            <td>Bacterial</td>
        </tr>
        <tr>
            <td>Viral</td>
        </tr>
    </tbody>
</table>

