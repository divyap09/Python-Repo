# SimPy (Simulation in Python)

- to create an environment to run simulations
```
environment_name = simpy.environment()
```

- to run the environment till T seconds
```
T = 10 #seconds
environment_name.run(until = T)
```

- to maintain a data structure for the model
```
queue_name = simpy.Store(environment_name)

queue_name.get()
queue_name.put(value)
```

- to get the elapsed time in the simulation
```
environment_name.now
```


to be added
-----------
yield
environment_name.timeout(value)  #does it takes in seconds?
while True loop
environment_name.process(method)
