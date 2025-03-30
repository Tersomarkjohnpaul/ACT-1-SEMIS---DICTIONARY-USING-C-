#include <iostream>
#include <string>
using namespace std;

int main(){
    string a;

    cout<<"Input your Word:";
    cin>>a;

    if (a== "ABACUS"){
        cout<<"A simple, ancient tool for arithmetic that uses rows of beads on rods or wires. It’s used for addition, subtraction, multiplication, and division, popular in ancient cultures for manual calculations.";
    }else if (a== "PASCALINE"){
        cout<<"A mechanical calculator invented by Blaise Pascal in the 1600s, designed to perform addition and subtraction. It works by turning gears, with each gear corresponding to a digit on the device’s display.";
    }else if (a== "NAPIER'S BONES"){
        cout<<"A set of rods invented by John Napier in the 1600s to simplify multiplication and division. Each rod is marked with numbers that can be arranged to calculate products more easily.";
    }else if(a== "LEIBNIZ WHEEL"){
        cout<<"A calculating machine invented by Gottfried Leibniz, capable of performing multiplication, division, and addition. It used a stepped drum to perform calculations automatically, a significant advancement in mechanical computation.";
    }else if (a== "TABULATING MACHINE"){
        cout<<"An early data-processing device, developed by Herman Hollerith. It used punched cards to read and sort data, especially useful for statistical analysis, such as in the US census of 1890.";
    }else if (a== "ANALYTICAL ENGINE"){
        cout<<"A proposed mechanical general-purpose computer by Charles Babbage in the 1830s, designed to perform any mathematical calculation. It featured an arithmetic logic unit, control flow, and memory, a precursor to modern computers.";
    }else if (a== "MARK 1"){
        cout<<"An early electromechanical computer developed by IBM and Harvard University in the 1940s. It was used for scientific calculations and was the first programmable computer, using punched tape for instructions.";
    }else if (a== "FIRST GENERATION COMPUTERS"){
        cout<<"The first computers, built from vacuum tubes, were large, slow, and generated a lot of heat. They used binary code and were often used for scientific, engineering, and military calculations.";
    }else if (a== "SECOND GENERATION COMPUTERS"){
        cout<<"These are the computers used transistors instead of vacuum tubes, making them smaller, faster, and more reliable. They were widely used for business applications, including accounting and payroll systems.";
    }else if (a== "THIRD GENERATION COMPUTERS"){
        cout<<"These are the computers used transistors instead of vacuum tubes, making them smaller, faster, and more reliable. They were widely used for business applications, including accounting and payroll systems.";
    }else{
        cout<<"Word not found";
    }

    return 0;
}

