# 9815_Final_Zhihao_Chen

Please download and unzip the 9815_final_Zhihao_CHen.tar.gz. It hasn't included the csv files we will need(the files are too large). I will email them to you instead, and please kindly add them to the /data directory. In case you want to test and generate the files yourself, simply uncomment the first line in the main function of main.cpp .

Make sure your Boost has been installed under the default directory. Navigate to the folder after unziping the file and copy&paste  the following command:

g++ -std=c++11 bondalgoexecutionservice.cpp positionservice.cpp pricingservice.cpp commonfunctions.cpp products.cpp executionservice.cpp riskservice.cpp historicaldataservice.cpp streamingservice.cpp main.cpp tradebookingservice.cpp marketdataservice.cpp -o executefile

Then run ./.executefile and you will get the result.

It might take more than 10 minutes to run because of the huge amount of data. 
