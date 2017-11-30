# Multi-threading
# multi-threading
# parallel computing.

1. create  thread
2. run , run , run , run
3. exit_thread, terminate_thread

# synchronization type of issue. lock
# racing issue. dead lock

#include<pthread.h>

void* thread_func(void* ptr);

int main()
{
  pthread_t t1 t2;
  char* s1 = "Thread 1"

  // creat_threads
  
  
  
  // run, run,run
  
  
  
  //exit


  return 0;
}



g++ Pthread.
passing argument to thread.
thread synchronization.

#include<iostream>
  
  use namespace std;
  void* My_Thread(void* ptr)
  {
      pthread_exit(NULL);
  }

int main()
{
    pthread_t t[N];
    // create;
    for(int i = 1; i < N; i++)
    pthread_create(, , My_Thread, )
    //run
    
    //termination


}

