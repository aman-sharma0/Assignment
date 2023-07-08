# Assignment

CREATE TABLE todo_list (
    task_id INT PRIMARY KEY,
    task_name VARCHAR(255),
    description VARCHAR(255),
    is_completed BOOLEAN
);

INSERT INTO todo_list (task_id, task_name, description, is_completed)
VALUES (1, 'Finish project', 'Complete the final report and submit it', FALSE);

INSERT INTO todo_list (task_id, task_name, description, is_completed)
VALUES (2, 'Buy groceries', 'Get milk, eggs, and bread', FALSE);

INSERT INTO todo_list (task_id, task_name, description, is_completed)
VALUES (3, 'Call John', 'Discuss the upcoming meeting', TRUE);
