# RDF2VEC

 the main is walk_experiments

# parameters
kg = file of the graph (.ttl)
page_rank_file = "data/pageranks_sorted_without_id.csv"
click_stream_file = "data/clickstream-enwiki-2017-11.tsv"
number_of_walks_per_resource = 250
depth = 8


to run call the method experiment_number()
and pass number of the strategy between 1 and 14

        1: uniform_weight,
        2: predicate_frequency_weight,
        3: inverse_predicate_frequency_weight,
        4: predicate_object_frequency_weight,
        5: inverse_predicate_object_frequency_weight,
        6: object_frequency_weight,
        7: inverse_object_frequency_weight,
        8: inverse_object_frequency_split_weight,
        9: page_rank_weight,
        10: inverse_page_rank_weight,
        11: page_rank_split_weight,
        12: inverse_page_rank_split_weight,
        13: click_stream_weight,
        14: inverse_click_stream_weight 
