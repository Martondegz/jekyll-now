---
layout: post
title: getters and  setters
---

You use the public set() function to request that an object change the parameter. The object takes the value(s) you offer to the set() command and do all the appropriate hidden work necessary to enact those changes, this may be database synchronization, thread blocking, it doesn't matter, and you don't need to know. That is the value of the set() command. You request, the object knows how to enact the request.<br /> 

The get command works the same way you request information from the get() command, this may also include the same mutex operations, perhaps now with a read-write (read portion) block so it doesn't block other getters. Again, you don't need to know all the synchronization manipulation necessary to carry out the task. You send the get() request, the object acts upon all the commands necessary to carry out the request, and then returns it.<br />


private String name;
    private String salutation;

    public void createSalutation() {
        this.salutation = greeting.greet(name);
    }

    public String getSalutation() {
        return salutation;
    }

    public void setName(String name) {
       this.name = name;
    }

    public String getName() {
       return name;
    }

