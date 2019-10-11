




// brain 2
DroneDeliveryBrain:
    trainer: ppo
    batch_size: 1024
    hidden_units: 32
    num_epoch: 6
    buffer_size: 10240
    learning_rate: 2.0e-4
    normalize: false
    num_layers: 1
    hidden_units: 256
    lambd: 0.95
    beta: 3.0e-3
    gamma: 0.9
    buffer_size: 1024
    max_steps: 5.0e5
    summary_freq: 2000
    time_horizon: 64
    epsilon: 0.2
    use_recurrent: false
    use_curiosity: false