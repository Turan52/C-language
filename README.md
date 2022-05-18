#include <iostream>
#include <queue>

int main() {
    std::queue<int> q;
    
    q.push(1);
    std::cout << q.front() << std::endl;
    q.push(2);
    std::cout << q.front() << std::endl;
    q.push(3);
    std::cout << q.front() << std::endl;
    
    q.pop();
    std::cout << q.front() << std::endl;
    q.push(4);
    std::cout << q.front() << std::endl;
    q.push(5);
    std::cout << q.front() << std::endl;
    q.pop();
    std::cout << q.front() << std::endl;
    q.pop();
    std::cout << q.front() << std::endl;
    q.pop();
}

