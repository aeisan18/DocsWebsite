# Create venv
python3 -m venv .venv

# Enter venv
source .venv/bin/activate

# Install zensical
pip install zensical

# Put it all together to install
python3 -m venv .venv && source .venv/bin/activate && pip install zensical

# Build with Zensical
zensical build

# Show zensical version
pip show zensical
