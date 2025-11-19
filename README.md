# DSA-STRIVER-2
### HASHING 
###### character hashinng 


### DSA
-ARRAYS -> https://github.com/Saujanya-rajvanshi/Striver
```cpp
#include<bits/stdc++.h>
using namespace std;

int main() {
string s;
cin >> s;

//pre compute
int hash [26] = {0};
for(int i = 0;i<s.size(); i++) {
    hash[s[i]]++;
}
int q;
cin >> q;
while(q -- ) {
    char c;
    cin >> c;
    // fetch 
    cout << hash [c] << endl ;
}
return 0;
}
```
{
    "version": "2.0.0",
    "tasks": [
        {
            "label": "run C",
            "type": "shell",
            "command": "cmd",
            "args": [
                "/c",
                "gcc ${file} -o ${fileDirname}\\${fileBasenameNoExtension}.exe && ${fileDirname}\\${fileBasenameNoExtension}.exe < ${fileDirname}\\input.txt > ${fileDirname}\\output.txt"
            ],
            "group": { "kind": "build", "isDefault": false },
            "problemMatcher": ["$gcc"]
        },
        {
            "label": "run C++",
            "type": "shell",
            "command": "cmd",
            "args": [
                "/c",
                "g++ ${file} -std=c++17 -o ${fileDirname}\\${fileBasenameNoExtension}.exe && ${fileDirname}\\${fileBasenameNoExtension}.exe < ${fileDirname}\\input.txt > ${fileDirname}\\output.txt"
            ],
            "group": { "kind": "build", "isDefault": true },
            "problemMatcher": ["$gcc"]
        },
        {
            "label": "run STL (C++)",
            "type": "shell",
            "command": "cmd",
            "args": [
                "/c",
                "g++ ${file} -std=c++17 -o ${fileDirname}\\${fileBasenameNoExtension}.exe && ${fileDirname}\\${fileBasenameNoExtension}.exe < ${fileDirname}\\input.txt > ${fileDirname}\\output.txt"
            ],
            "group": { "kind": "build", "isDefault": false },
            "problemMatcher": ["$gcc"]
        },
        {
     


    
    if(p1.first < p2.first) return true;
    else return false ;
}





       "label": "run Java",
            "type": "shell",
            "command": "cmd",
            "args": [
                "/c",
                "javac ${file} && java -cp ${fileDirname} ${fileBasenameNoExtension} < ${fileDirname}\\input.txt > ${fileDirname}\\output.txt"
            ],
            "group": { "kind": "build", "isDefault": false },
            "problemMatcher": ["$javac"]
        },
        {
            "label": "run Python (with I/O)",
            "type": "shell",
            "command": "cmd",
            "args": [
                "/c",
                "python ${file} < ${fileDirname}\\input.txt > ${fileDirname}\\output.txt"
            ],
            "group": { "kind": "build", "isDefault": false },
            "problemMatcher": []
        },
        {
            "label": "run Python (terminal output)",
            "type": "shell",
            "command": "python",
            "args": ["${file}"],
            "group": { "kind": "build", "isDefault": false },
            "problemMatcher": []
        },
        {
            "label": "run JavaScript",
            "type": "shell",
            "command": "node",
            "args": ["${file}"],
            "group": { "kind": "build", "isDefault": false },
            "problemMatcher": []
        },
        {
            "label": "run SQL (SQLite3)",
            "type": "shell",
            "command": "cmd",
            "args": [
                "/c",
                "sqlite3 ${fileDirname}\\database.db < ${file}"
            ],
            "group": { "kind": "build", "isDefault": false },
            "problemMatcher": []
        },
        {
            "label": "open HTML/CSS",
            "type": "shell",
            "command": "cmd",
            "args": [
                "/c",
                "start ${file}"
            ],
            "group": { "kind": "build", "isDefault": false },
            "problemMatcher": []
        }
    ]
}
```


