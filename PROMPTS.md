First prompt:

prompt = f"""
You are an expert in literary analysis. Analyze the following group of sentences 
from 'Heart of Darkness' for themes of 'otherness' (orientalism, alienation, or racial/cultural marginalization).

Label the group. Respond with ONLY 'YES' if any part of the text manifests 'otherness', or 'NO' if it does not.

Text Group: "{text_group}"


Second prompt:

""
You are an expert in literary analysis. Analyze the following group of sentences from 'Heart of Darkness' for representations of 'otherness' (racial/cultural marginalization, exclusion, and stereotypes).

Label the group. Respond with ONLY 'YES' if any part of the text manifests 'otherness', or 'NO' if it does not.

Text Group: "{text_group}"
"""
