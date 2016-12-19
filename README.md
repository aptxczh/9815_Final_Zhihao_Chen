# 9815_Final_Zhihao_Chen

Please download and unzip the 9815_final_Zhihao_CHen.tar.gz. It has included the csv files we will need(for sake of speed). In case you want to test and generate the files yourself, simply uncomment the first 4 lines of codes in the main function of main.cpp .

Make sure your Boost has been installed under the default directory. Navigate to the folder after unziping the file and copy&paste  the following command:

g++ -std=c++11 bond_algo_execution_service.cpp position_service.cpp pricing_service.cpp common_functions.cpp products.cpp execution_service.cpp risk_service.cpp historical_data_service.cpp streaming_service.cpp main.cpp trade_booking_service.cpp market_data_service.cpp -o executefile

Then run ./.executefile and you will get the result.

It might take more than 10 minutes to run because of the huge amount of data. Instead, you may test the program by changing the corresponding number of data generated. 
