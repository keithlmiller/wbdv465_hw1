wbdv465_hw1
===========

Final Application Outline

Social Media Application
App Name: Photoshop Battle (maybe something other than Photoshop because of copyright)

Users - username, email, password
    
        
    Moderators
        can manage all creators
        can manage all battles
        can manage all photos
        can manage all PhotoReplies

    Creators 
        can create battles
        can delete their own battles
        can create photos
        can create PhotoReplies
        can manage their own PhotoReplies
        

Battle - creator, name, description, origin_photo

    belongs to a user (creator)
    has a photo
    can have many PhotoReplies

Photo - creator, battle_name, name, description

    belongs to a Battle

PhotoReply - creator, battle_name, name, description, parent_photo, 

    belongs to a battle
    belongs to a photo or photoreply
    can have many photoreplies



