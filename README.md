## Dataset Settings
- To use SD dataset: <br>
    dataset_type = "SD" <br>
    dataset_location = "Final_LUDV0_Sub/Code/src/classifier/data/sd_dataset"
- To use MD dataset: <br>
    dataset_type = "MD" <br>
    dataset_location = "Final_LUDV0_Sub/Code/src/classifier/data/md_dataset"

## DQN Algorithm Settings
- To use DQN algorithm: <br>
    dqn_type = "DQN" 
- To use Double DQN algorithm: <br>
    dqn_type = "DoubleDQN"
- To use prioritized experience replay: <br>
    prioritized_replay = True
    
## Running different models
- To run Flat-DQN: <br>
    agent_id = "agentdqn" <br>
    disease_as_action = True <br>
    use_all_labels = False
    
- To run HRL: <br> 
    agent_id = "agenthrljoint2" <br>
    allow_wrong_disease = False <br>
    wrong_disease_knowledge = False <br>
    sf_idf_knowledge = False <br>
    disease_as_action = False <br>
    classifier_type = "deep_learning" <br>
    use_all_labels = True

- To run FA-SIDA with only UER: <br>
    agent_id = "agenthrljoint2" <br>
    allow_wrong_disease = True <br>
    wrong_disease_knowledge = True <br>
    sf_idf_knowledge = False <br>
	disease_as_action = False <br>
	classifier_type = "deep_learning" <br>
	use_all_labels = True

- To run FA-SIDA with only DS-KG: <br>
    agent_id = "agenthrljoint2" <br>
    allow_wrong_disease = True <br>
    wrong_disease_knowledge = False <br>
    sf_idf_knowledge = True <br>
	disease_as_action = False <br>
	classifier_type = "deep_learning" <br>
	use_all_labels = True

- To run FA-SIDA: <br>
    agent_id = "agenthrljoint2" <br>
    allow_wrong_disease = True <br>
    wrong_disease_knowledge = True <br>
    sf_idf_knowledge = True <br>
	disease_as_action = False <br>
	classifier_type = "deep_learning" <br>
	use_all_labels = True
