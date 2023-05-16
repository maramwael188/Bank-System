cmake_minimum_required(VERSION 3.21)
project(BANKAPP)

set(CMAKE_CXX_STANDARD 14)

add_executable(BANKAPP main.cpp BankApp.cpp SavingsBankAccount.cpp Client.cpp BankAccount.cpp)
