// factorial
//factorial program using recursion

int fact(int n){
if(n == 0){
return 1;
}

int ans = fact(n-1);

return ans*n;
}

int main(){
int n;
cin>>n;
cout<<fact(n)<<endl;
}
