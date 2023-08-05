void copyStack(stack<int>& stack1, stack<int>& stack2)
{
   int size = stack1.size();
   while(size > 0)
   {
 
      stack2.push(stack1.top());
      stack1.pop();
      stack1.push(stack2.top());
      --size;
      
   }
   

}
