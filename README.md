# SQL_Ass-2

CREATE TABLE students (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  name TEXT,
  age INTEGER,
  gender TEXT
);

INSERT INTO students (name, age, gender) VALUES
  ('John', 20, 'Male'),
  ('Jane', 19, 'Female'),
  ('Bob', 21, 'Male');
  
  SELECT * FROM students;
  UPDATE students SET name = 'Janet' WHERE id = 2;
  DELETE FROM students WHERE id = 3;
  SELECT * FROM students;
  
