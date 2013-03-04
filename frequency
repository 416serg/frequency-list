def build_ranking_to_frequency(l):
    new_dict = {}
    for item in range(len(l)):
        if tuple(l[item]) not in new_dict.keys():
            new_dict[tuple(l[item])] = 1
        else:
            new_dict[tuple(l[item])] += 1 
    return new_dict
