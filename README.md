# Strong-Password
Hacker Rank (Problem Solving)

int minimumNumber(int n, string password) {
   
    int a=0,b=0,c=0,d=0,req;
  
        for (int i=0; i<n; i++) {
        if(isupper(password[i])){
           a=1;
        }
        else if(islower(password[i])){
        b=1;
        }
        else if (isdigit(password[i])) {
        c=1;
        }else {
        d=1;
        }
    }
    
    req=4-(a+b+c+d);
    if(n+req<6){
    return 6-n;
    }else {
      req;
    }
    
    return req;
    
  
}
