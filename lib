// Import necessary traits and types
use pebbles_game_io::{Metadata, In, InOut, Out, PebblesInit, PebblesAction, PebblesEvent, GameState, Player, DifficultyLevel};
use gstd::prelude::*;

// Define the PebblesMetadata type
pub struct PebblesMetadata;

// Implement Metadata for PebblesMetadata
impl Metadata for PebblesMetadata {
    type Init = In<PebblesInit>;
    type Handle = InOut<PebblesAction, PebblesEvent>;
    type State = Out<GameState>;
    type Reply = ();
    type Others = ();
    type Signal = ();
}
