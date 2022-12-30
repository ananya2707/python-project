# Initialize the lists
names = ['Arindom', 'Blessan', 'Thelei', 'Mehdee']
marks = [80, 75, 50, 95]
updates = [68, 86, 100, 76]

# Update the marks
for i in range(len(names)):
  marks[i] += updates[i]

# Find the student with maximum marks
max_mark = 0
max_mark_index = 0
for i in range(len(names)):
  if marks[i] > max_mark:
    max_mark = marks[i]
    max_mark_index = i

# Find the rank of the student with maximum marks
rank = 1
for i in range(len(names)):
  if marks[i] > marks[max_mark_index]:
    rank += 1

# Find the previous rank
prev_rank = rank
for i in range(len(names)):
  if marks[i] > marks[max_mark_index] and updates[i] < updates[max_mark_index]:
    prev_rank += 1

# Print the results
print("The student with maximum marks after updation is", names[max_mark_index])
print("Their rank has jumped from", prev_rank, "to", rank)

