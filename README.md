### Hi there 👋
```cpp
class Me{
    public:
        string name = "ChenGuoXiang";
        int age = 20;
        string address="Taiwan,Taichung";
        string email = "s1411232069@ad1.nutc.edu.tw";
        string web = "ChenGuoXiang940.github.io";
};

class About: public Me{
    private:
        string hobbies[5] = {"Reading","Coding","Gaming","Music"};
    public:
        void showHobbies(){
            for(int i=0;i<5;i++)
                cout<<hobbies[i]<<endl;
        }
};

class Knowledge: public Me{
    private:
        string skills[7] = {"C#","C++","C","Python","Java","Html/Css","JavaScript"};
    public:
        void showSkills(){
            for(int i=0;i<7;i++)
                cout<<skills[i]<<endl;
        }
};
```
<!--
**ChenGuoXiang940/ChenGuoXiang940** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
