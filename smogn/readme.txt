# AutoSMOGN

One Paragraph of project description goes here

## Getting Started

This project is used for modeling and machine learning applications in the Sewer. Applicable disciplines of the project:Environmental Science and Engineering, Water Supply and Drainage Science and Engineering, Civil Engineering, Municipal Engineering, Resources and Environment, Environmental Informatics, Machine Learning, Deep Learning

### Prerequisites

You need the environment of python3,third party library of pandas,openpyxl,numpy

### Installing

You can get it by pip install AutoSMOGN

    pip install AutoSMOGN

## Example
difference_sequence is the environmental indicator to be constructed. The first column is the number space you define, the second column is the sampling method you define, and the third column is constant 0.
```
difference_sequence=[('50','1','0'),
('40','1','0'),
('30','1','0'),
('20','1','0'),
('10','0','0')]

# print(train.describe(),test.describe())
print(train.shape,test.shape)


after_train_excel,after_test_excel=wwtp_data_opt(f_train='./dataset/pre_train.xlsx', f_test='./dataset/pre_test.xlsx', difference_sequence=difference_sequence)
after_train=pd.read_excel(after_train_excel)
after_test=pd.read_excel(after_test_excel)
# print(after_train.describe(),after_test.describe())
print(after_train.shape,after_test.shape)

```

## Versioning

0.1.1

## Authors

*   **Yin wanxin** -*Liaoning university, Shenyang*- *Main work*

*   **Wang yuqi** -*Harbin Institute of Technology,shenzhen*- *team members*

*   **Wang HongCheng** -*Harbin Institute of Technology,shenzhen*- *tutor*

*   **Wang AiJie** -*Harbin Institute of Technology,shenzhen*- *tutor*

*   **Lv JiaQiang** -*Harbin Institute of Technology*- *team members*

*   **Chen JiaJi** -*Chinese Academy of Sciences*- *team members*

## License

GPL

## Acknowledgments

*Liaoning university, Shenyang*
