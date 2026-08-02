# Loop-Topic-IntershipDay-2
#include<iostream>
using namespace std;
int main(){
    
    for(int i=10;i>=1;i--){
        cout<<"The Counting of  Reverse Numbers are :"<<i<<endl;
    }
    return 0;
}


# 2nd Program 
#include<iostream>
using namespace std;
int main() {
    
    for(int i=1; i<=10; i++) {
        cout<<"\n The Counting from Numbers are :"<<i<<endl;
    }
    return 0;
}

#3rd Program 
#include<iostream>
using namespace std;
int main() {
int num;
    
  cout<<"\n enter any num here:";
  cin>>num;
   
    for(int i=1;i<=10; i++)  {
        cout<<num*i<<endl;
    }
    return 0;
}

#4th Program 
#include<iostream>
using namespace std;
int main() {
int sum=0;
    
  
    for(int i=1;i<=10; i++)  {
        cout<<i<<endl;
        sum=sum+i;
    }
    cout<<"\n Your sum of NUmbers are:"<<sum;
    return 0;
}

#5th Program (Even Numbers)
#include<iostream>
using namespace std;
int main() {
    
    for(int i=2;i<=100;i+=2) {
    cout<<"\n Your Even Numbers are:"<<i;
}
 return 0;
}

#6th Program (odd Numbers)
#include<iostream>
using namespace std;
int main() {
    
    for(int i=1;i<=100;i+=2) {
    cout<<"\n Your Odd Numbers are:"<<i;
}
 return 0;
}

#7th Program 
#include<iostream>
using namespace std;
int main() {
    
    for(int i=1;i<=5;i++) {
   cout<<"$";
}
 return 0;
}
#8th Program 
#include<iostream>
using namespace std;
int main() {
    
    for(int r=1;r<=3;r++) { //outside loop(rows)
        
     for(int s=1;s<=10;s++){ //inner loop(stars)
         cout<<"*";
     }
       cout<<endl;
    }
    return 0;
}



#9th Program 

#include<iostream>
using namespace std;
int main() {
    int row;
    
    cout<<"\n enter the rows you want:";
    cin>>row;
    
    for(int i=1;i<=row;i++) { //outside loop(rows)
        
     for(int s=1;s<=i;s++){ //inner loop(stars)
         cout<<"*";
     }
       cout<<endl;
    }
    return 0;
}

#10th program 
#include <iostream>
using namespace std;

int main() {
    for (int i = 1; ; i++) { // Condition nahi di
        cout << "Number: " << i << endl;
        
        if (i == 120) {
            break; // 120 aate hi loop ko zabardasti rok diya
        }
    }
    return 0;
}
