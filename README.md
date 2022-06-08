this is an implementation of trainging split cifar 10 tasks by owm method

in dir owm_lhj 
    
    python run_owm_cifar10.py


in optim_owm.py, I apply orthogonal weight modifications in weights updating.

the netwrok structure is in OWMnet.py

in split-cifar10.py, I divide the cifar10 tasks into 5 sub tasks

| task1  | task2  |  task3  |   task4  |  task5  |
|--------|---------|--------|----------|---------|
|airplane, ship|automobile, truck|bird, frog|cat, dog|deer, horse|
