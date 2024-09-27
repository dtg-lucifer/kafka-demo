# How to run

> **Step 1:**
> 	*Run the docker containers*
```bash
docker-compose up
```

> **Step 2:**
> 	*Run the admin to create topic*
```bash
node admin.js
```

> **Step 3:**
> 	*Run consumer within a predefined group*
```bash
node consumer.js grp-1
```

> **Step 4:**
> 	*Run the producer to produce messages*
```bash
node producer.js

> thor south
> tony north
> wanda south
```
