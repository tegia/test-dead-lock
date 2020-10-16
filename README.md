# Program stacktracer.py is used to determine dead lock
# How to use
import stacktracer
stacktracer.trace_start("trace.html")

stacktracer creates report trace.html with format str(datetime.now())+ "_" + "trace.html") with interval 5s

stacktracer extract thread info and check whether info contains lock

# Example
See another_dead_lock.py and dead_lock.py

Run
python3 another_dead_lock.py
and you will see report each interval 5s
