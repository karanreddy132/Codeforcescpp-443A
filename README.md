# Codeforcescpp-443A
#include <bits/stdc++.h>

using namespace std;

int main(){
  string s;
  set <char> str;
  getline(cin,s);
  int len = s.length();
  for(int i=0;i<len;i++){
    if(s[i]>='a' && s[i]<='z'){
      str.insert(s[i]);
    }
  }
  cout << str.size();
  return 0;
}
