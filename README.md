## About the game itself
- Original name
  - No clue yet

#

- 2D or 3D
  - 3D, makes it more interactive and easier to place obstacles

#

- Theme (ties in with name)
  - No clue yet

#

- Game mechanics
  - Similar to how the actual game works or something, still need to research on this game.

#

- Do we create a lobby or how should matchmaking be done
    - I had 2 ideas for this.
        * Server Browser: Using MessagingService send messages to each server for new lobbies
        * Boxes: We have boxes for players to go into to join a match and the first player will be the leader

#

- Can characters collide?
  - We can have different modes, one where collision is enabled and one where collision is disabled

#

- Which platforms do we support (PC, consoles, mobile)?
  - At first, I think we should target PC and then add support for other platforms. Since PC is the most used platform afaik.

#

# Workflow as a team
- How should communication be done? Create our own Discord server? Get our own channel in this Discord?
  - I think a generalized Discord server where we have all the developers and channels for different games, that would crowd this server less with channels. I think Panda should create it, and no one gets more perms besides Ruben and Panda, to keep it fair. It would also be easier to manage webhooks since we'd be having an Admin System in each game, we should have a different channel for each one with a designated webhook for organization.

#

- Ideally I would like to work through git + rojo (partially managed). All the requirements are made in the form of issues on github/gitlab/any other, and MR will be made for each requirement so that we can easily track progress and who made what. But since most of you don’t know git/rojo. This doesn’t very reasonable.
  - I mean, Rojo and Git isn't that hard to setup. We can just write an instructional paragraph for everyone to set it up and if anyone needs help we can help them out. It would also help with version control.

#

- So more realistically we create a group and work through team create. But this does come with several issues such as no version control, (which includes hard to track who did what, go back to a previous version if things don’t work, don’t know who made something break etc).
  - I think we can just have a rank in the main RSA group for "Exclusive Devs" and we just publish our game on there. Since having a group for each game seems a bit expensive in the long run.
