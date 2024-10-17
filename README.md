# rule_engine_with_AST
class Node:
    def __init__(self, node_type, left=None, right=None, value=None):
        self.type = node_type  # "operator" or "operand"
        self.left = left       # reference to left child
        self.right = right     # reference to right child
        self.value = value     # value for operand nodes (e.g., age > 30)
