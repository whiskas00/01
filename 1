import csv

F = open("task14.csv")
csvv = [i for i in csv.reader(F, delimiter=",")]

allTask = list(set([i[3] for i in csvv]))
allClasses = sorted(list(set([int(i[2]) for i in csvv])))
allTaskCount = [0] * len(allTask)
allClassesCount = [0] * len(allClasses)
allTaskSumma = [0] * len(allTask)
allClassesSumma = [0] * len(allClasses)

for i in csvv:
    if i[0] == "Колесникова" and i[1] == "Ксения":
        print(f"Ты получил: {i[4]}, а за предмет {i[3]}")

for i in csvv:
    classMember = int(i[2])
    task = i[3]
    taskGrade = int(i[4])
    allClassesCount[allClasses.index(classMember)] += 1
    allClassesSumma[allClasses.index(classMember)] += taskGrade
    allTaskCount[allTask.index(task)] += 1
    allTaskSumma[allTask.index(task)] += taskGrade

with open("students_new.csv", "w") as csvfile:
    spamwriter = csv.writer(csvfile, delimiter=";")
    for i in allClasses:
        spamwriter.writerow([i, round(allClassesSumma[allClasses.index(i)] / allClassesCount[allClasses.index(i)], ndigits=3)])

    for i in allTask:
        spamwriter.writerow([i, round(allTaskSumma[allTask.index(i)] / allTaskCount[allTask.index(i)], ndigits=3)])
