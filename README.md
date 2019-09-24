# Human_Activity_Recoginition_using_smart_phone_data
<h2>
1.By using LSTM 2 layer architecture we got 93% model accuracy so by refering this paper we use a divide and conquer apporach to get some more accuracy than LSTM models Refer: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5949027/

2.So we splitting the data into 2 models one model contains 3 class labels and another contains another 3 class labels like 'STANDING,SITTING,LYING' consider as one model called static model and 'WALKING UPSTSAIRS,WALKING DOWNSTAIRS,WALKING' as another model called dynamic model

3.First we create a binary model i.e.., we set >3 class labels as 1 and < 3 class labels as 0

4.second we create a model for > 3 class labels and predict also called as static model

5.Third we create a model for < 3 class labels and predict also called as dynamic model

Refer the above paper for to get some more better understading the way of implementation
</h2>
