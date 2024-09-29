Hello! I'm Lian Barreto, I live in Brazil, and i was born in 2013.
I am a Developer on Roblox but i actually don't know much about Lua programming language, just learnt how to make a button make frame visble:

local btn = script.Parent -- Refers to the button. LocalScript should be Child of the Button
local frame = script.Parent.Parent.Frame -- Frame name (Change "Frame" for its name)

button.MouseButton1Click:Connect(function()
  frame.Visible = not frame.Visible -- This line makes the button disable and enable the frame. Delete it if u want another type
  frame.Visible = true -- This line makes the button only enable the frame. Delete if if you want another type
  frame.Visible = false -- This line makes the button only disable the frame. Delete if if you want another type

-- watch out! there could be only one line of these three shown up here.
  end
end)

That's all. Thanks for viewing!
