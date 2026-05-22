

# MiniMax

- set env variables in .zshrc first

```
# minimax
export OPENAI_API_KEY="sk-cp-2K0xzupMArDDQIAzbkgbii0nl8Z-2HXBb53r0GrGfF5QeOdBE1RFWABiXo01646KHz3s-ku5bUNclEHNoE7pErxiARe3tXqGac2tuHHnxIf_FH2M4novh9w"
export OPENAI_BASE_URL="https://api.minimax.chat/v1"
export OPENAI_API_BASE="https://api.minimax.chat/v1"
export MINIMAX_GROUP_ID="2030821106625028632"
```

then run:

```
export OPENAI_EXTRA_HEADERS='{"X-Group-Id": $MINIMAX_GROUP_ID}'

python ai_scientist/perform_ideation_temp_free.py \
 --workshop-file "ai_scientist/ideas/my_research_topic.md" \
 --model minimax-M2.7 \
 --max-num-generations 20 \
 --num-reflections 5
```