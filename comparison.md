## Comparison between models

1. First model(main): 
num_of_epochs = 40
image_size = (640, 640)

- Box(P)(all): 0.905
- Recall(all): 0.651
- map50(maximum): 0.721
- map50-95(maximum): 0.511

2. Second model(main2):
num_of_epochs = 50
image_size = (640, 640)

- Box(P)(all): 0.634
- Recall(all): 0.714
- map50(maximum): 0.746
- map50-95(maximum): 0.542

3. Third model(mainh):
num_of_epochs = 50
image_size = (1024, 1024)

- Box(P)(all): 0.694
- Recall(all): 0.638
- map50(maximum): 0.721
- map50-95(maximum): 0.487

4. Fourth model(mainh2):
num_of_epochs = 100
image_size = (1024, 1024)

- Box(P)(all): 0.766
- Recall(all): 0.697
- map50(maximum): 0.692
- map50-95(maximum): 0.468